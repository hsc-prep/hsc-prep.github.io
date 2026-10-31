# StudyStrides

GitHub Pages home for the StudyStrides course sites. Smart steps · Strong results.

- [StudyStrides · HSC SOR](https://hsc-prep.github.io/sor/) opens the live Studies of Religion course site.
- [StudyStrides · HSC Geography](https://hsc-prep.github.io/geo/) opens the Geography course site.
- [About Us](https://hsc-prep.github.io/about/)
- [Contact Us](https://hsc-prep.github.io/contact/)

Logo files live in `assets/`. Favicons sit in the site root.

## Contact form

The contact form posts to [FormSubmit](https://formsubmit.co/hsc.prep.site@gmail.com) so messages are emailed to `hsc.prep.site@gmail.com`. No API key or other secret is stored in this repo.

Paul needs to activate it once before messages arrive:

1. Open the [contact page](https://hsc-prep.github.io/contact/) and send a test message (name, email, and a short note).
2. Open the confirmation email FormSubmit sends to `hsc.prep.site@gmail.com` and confirm the address.
3. After that, each submission is delivered to that inbox. The sender’s address is the Email field, so replies can go straight back.

The form then returns the visitor to `https://hsc-prep.github.io/contact/?sent=1`, which shows a short thank-you line.

Optional later: on FormSubmit’s confirmation page, turn on an email alias and replace `hsc.prep.site@gmail.com` in `contact/index.html` with that alias. The public page will stop showing the inbox address, and delivery stays the same.

To use Formspree instead, create a form at [formspree.io](https://formspree.io/) for `hsc.prep.site@gmail.com` and change the form `action` in `contact/index.html` to `https://formspree.io/f/yourFormId`. Put the form id in the page only after the form exists. Do not commit a Formspree secret key.
