# How Big is Baby Today — Support & Privacy site

A single static page (`index.html`) that serves as both the **Support URL** and the
**Privacy Policy URL** for the App Store listing. Contact email: elias.irick97@gmail.com

## Publish it free with GitHub Pages

1. Create a new **public** repo on GitHub, e.g. `how-big-baby-support`.
2. Upload `index.html` to the repo root (drag it onto the GitHub web page, or push it).
3. In the repo: **Settings → Pages → Build and deployment**.
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`) and folder `/ (root)` → **Save**
4. Wait ~1 minute. Your page goes live at:
   `https://<your-username>.github.io/how-big-baby-support/`

## Use the URL in App Store Connect

- **Support URL** (App Information, and on the 1.0 version page): paste the Pages URL.
- **Privacy Policy URL** (App Privacy section): paste the same URL, or append
  `#privacy` to jump to the policy section: `…/how-big-baby-support/#privacy`

## Alternatives (no GitHub)

- **Carrd** (carrd.co): create a free one-page site and paste the Support and Privacy
  text from `index.html`.
- **Notion**: make a page, Share → Publish to web, use that URL.

Update the "Last updated" date in `index.html` if you change the policy later.
