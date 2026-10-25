# nusara.github.io

Company website for Nusara Trading, hosted free on GitHub Pages.

Live at: https://nusara.github.io (after step 3 below)

## Publish it

1. The repository **must** be named exactly `nusara.github.io` and live under the GitHub account (or organization) called `nusara`. If the account has a different name, the site will be at `<account-name>.github.io` instead.
2. Upload the files:
   ```bash
   git clone https://github.com/nusara/nusara.github.io.git
   cd nusara.github.io
   # copy index.html, README.md, .nojekyll into this folder
   git add .
   git commit -m "First version of Nusara website"
   git push
   ```
   Or drag and drop the files on github.com: **Add file > Upload files**.
3. On GitHub: **Settings > Pages > Build and deployment**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Wait 1 to 2 minutes and open https://nusara.github.io.

The repo must be **public** on a free account for Pages to work.

## Before going live: fill in the TODOs

Search `index.html` for `TODO`:

- Email address (replace `info@example.com` once email is set up)
- Phone / WhatsApp number (format for wa.me link: country code + number, no `+` or spaces)
- City for the company address

Also check the product texts with Ve: grades, origins and forms (e.g. cassia cinnamon, black/green tea) are placeholders that should match what the suppliers actually offer.

## Editing

Everything is in one file, `index.html` (HTML, CSS in the `<style>` block, a small script at the end). Colours are defined at the top of the CSS under `:root`.

Ideas for next steps:

- Add real product photos in an `images/` folder (WebP, under 300 KB each).
- Add a product spec sheet (PDF) per product for buyers.
- Add an Indonesian (`/id/`) or Swedish version if needed.
- A contact form: GitHub Pages is static only, so use a free form service (e.g. Formspree) or keep the mailto link.

## Custom domain later

When a domain is bought (e.g. nusara.se), add it under **Settings > Pages > Custom domain**, add the DNS records described in the setup guide, then tick **Enforce HTTPS**. GitHub creates a `CNAME` file in the repo automatically.
