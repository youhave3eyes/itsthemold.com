# itsthemold.com

Mold and mycotoxin education website. Sister site to itstheparasites.com, same layout and style.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site: walkthrough, mold profiles, house explorer, humidity dial, solutions (HOCl, chlorine dioxide gas), body detox |
| `logo.svg`, `logo-icon.svg` | Logo files |
| `favicon-32.png`, `apple-touch-icon.png`, `og-image.png` | Browser icon and link-preview image |
| `CNAME` | Connects the site to the itsthemold.com domain |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `itsthemold`).
2. Click **Add file → Upload files**, drag in everything from this folder, and commit.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.

## Connect your domain

At your domain registrar (for example IONOS), add:

- Four **A** records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- A **CNAME** record for `www` pointing to `YOUR-USERNAME.github.io`

Then in **Settings → Pages**, enter `itsthemold.com` as the custom domain and tick **Enforce HTTPS**.

## Making changes

- **House hot spots:** search `index.html` for `HOUSE EXPLORER` to edit the text for each room.
- **What-works ladder:** search for `WHAT WORKS LADDER` to change rows or scores.
- **Your own product or affiliate links:** add them in the HOCl and chlorine dioxide cards (search `Hypochlorous acid` and `Chlorine dioxide gas`).
