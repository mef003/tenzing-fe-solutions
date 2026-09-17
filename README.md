# Tenzing FE Solutions Ltd — GitHub Pages starter site

This starter site contains:

- `index.html` — main landing page
- `contact.html` — contact / enquiry page
- `style.css` — Tenzing black, gold and cream styling

## Publish on GitHub Pages

1. Create a public GitHub repository called `tenzing-fe-solutions`.
2. Upload the three files in this folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**.
6. Save.
7. GitHub will give you a live address such as:
   `https://YOURUSERNAME.github.io/tenzing-fe-solutions/`

## Make the contact form work

The form currently contains:

`https://formspree.io/f/YOUR-FORM-ID`

Create a free Formspree form, copy your form endpoint, and replace the placeholder in `contact.html`.

## Next improvements

- Replace the triangle placeholder with the official Tenzing logo.
- Add a real hero image if desired.
- Add About, Case Studies, Insights and Privacy pages.
- Connect a custom domain later.
/* Final mobile hero refinement */

@media (max-width: 768px) {

  .hero {
    padding-top: 70px;
    padding-bottom: 70px;
  }

  .hero h1,
  .hero-title,
  h1 {
    font-size: clamp(2.7rem, 11vw, 3.8rem);
    line-height: 1.03;
    letter-spacing: -0.025em;
    margin-bottom: 28px;
  }

  .hero p,
  .hero-copy,
  .hero-description {
    font-size: 1.1rem;
    line-height: 1.55;
    margin-bottom: 30px;
  }

  .hero .eyebrow,
  .eyebrow,
  .kicker,
  .overline {
    font-size: 0.82rem;
    letter-spacing: 0.28em;
    line-height: 1.6;
    margin-bottom: 28px;
  }

  .hero .btn,
  .hero a.btn,
  .cta-button {
    width: 100%;
    text-align: center;
    padding: 16px 18px;
  }
}
