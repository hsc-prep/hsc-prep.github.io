# StudyStrides

GitHub Pages home for the StudyStrides course sites. Smart steps · Strong results.

Live at [studystrides.com.au](https://studystrides.com.au/) (the `CNAME` file sets this; the old `hsc-prep.github.io` address redirects here).

- [StudyStrides · HSC SOR](https://sor.studystrides.com.au/) opens the Studies of Religion course site.
- [StudyStrides · HSC Geography](https://studystrides.com.au/geography/) shows the Geography "coming soon" page.
- [About Us](https://studystrides.com.au/about/)
- [Contact Us](https://studystrides.com.au/contact/)

Logo files live in `assets/`. Favicons sit in the site root.

## Forms

The contact form and the For Schools form post to the shared StudyStrides send-form endpoint at `https://vjcvlfkrhshydjpldaxo.supabase.co/functions/v1/send-form`. No API key or other secret is stored in this repo.

After a successful send, the visitor returns to the same page with `?sent=1`, which shows a short thank-you. On the For Schools page, that thank-you also asks the school to fill in the options page for the course they chose. If sending fails, the page shows `?error=1` and asks the visitor to email support@studystrides.com.au. Replies go to the address entered in the email field.
