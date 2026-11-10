# StudyStrides

GitHub Pages home for the StudyStrides course sites. Smart steps · Strong results.

Live at [studystrides.com.au](https://studystrides.com.au/) (the `CNAME` file sets this; the old `hsc-prep.github.io` address redirects here).

- [StudyStrides · HSC SOR](https://sor.studystrides.com.au/) opens the Studies of Religion course site.
- [StudyStrides · HSC Geography](https://studystrides.com.au/geography/) shows the Geography "coming soon" page.
- [About Us](https://studystrides.com.au/about/)
- [Contact Us](https://studystrides.com.au/contact/)
- [Privacy Notice](https://studystrides.com.au/privacy/)
- [Terms of Access](https://studystrides.com.au/terms/)
- [Refunds and Cancellations](https://studystrides.com.au/refunds/)

Logo files live in `assets/`. Favicons sit in the site root.

## Contact form

The contact form posts to FormSubmit using the activated alias string in `contact/index.html` (not the inbox address), so the support inbox does not appear on the public page. No API key or other secret is stored in this repo.

After sending, the form returns the visitor to `https://studystrides.com.au/contact/?sent=1`, which shows a short thank-you line. Replies go straight back to the address entered in the Email field.
