# Promarket BD (প্রোমার্কেট বিডি) — Official Website

**Shaping the Future with AI & Modern Tech Solutions**

A responsive, bilingual (English & Bengali) landing page built for **Promarket BD**, optimized for instant deployment on **GitHub Pages**.

## Project Structure

```text
promarket-bd-website/
├── index.html          # Main landing page
├── 404.html            # Custom GitHub Pages 404 error page
├── .nojekyll           # Prevents GitHub Pages Jekyll build issues
├── README.md           # Project documentation
└── assets/
    ├── css/
    │   └── style.css   # Custom scrollbar & styling rules
    └── js/
        └── main.js     # Interactive menu, form validation, neural canvas
```

## How to Publish on GitHub Pages

1. Create a new public repository on [GitHub](https://github.com/new) (e.g., `promarket-bd`).
2. Upload all files inside this folder (`index.html`, `404.html`, `.nojekyll`, `README.md`, and the `assets/` folder) to the root of your repository.
3. Go to your repository **Settings** → **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Wait 1–2 minutes and refresh the page to get your live `https://<username>.github.io/<repo-name>/` URL.

## Customization Notes
- Replace placeholder `https://www.facebook.com` and `https://m.me` links in `index.html` with your official Promarket BD Facebook Page and Messenger URLs.
- To receive real email submissions from the contact form on static hosting, connect the form `action` attribute to a free service like [Formspree](https://formspree.io/) or [Web3Forms](https://web3forms.com/).
