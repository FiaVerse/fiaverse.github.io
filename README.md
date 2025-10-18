# fiaverse.me — Static Clone

This is a static, single-page clone ready for **GitHub Pages**. It mirrors the content structure of *fiaverse.me* and includes **placeholders for 6 videos** (Google Drive embeds).

## Replace video placeholders
1. Open `index.html`
2. Find each `<iframe src="">`
3. Paste your Google Drive preview link, e.g.:
   `https://drive.google.com/file/d/FILE_ID/preview`

## Publish on GitHub Pages
1. Create a repo (e.g., `fiaverse`)
2. Upload these files
3. Go to **Settings → Pages**
   - Source: *Deploy from a branch*
   - Branch: `main` (or `master`) / root
4. Wait for build; your site will be live at `https://YOUR-USER.github.io/fiaverse/`

## Add your custom domain
1. In **Settings → Pages**, add your domain (e.g., `fiaverse.me`)
2. Create the DNS records at your registrar:
   - `A` records to GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Optionally add `www` as a `CNAME` to `YOUR-USER.github.io.`
3. GitHub will create a `CNAME` file automatically when you set the custom domain in settings.

## Notes
- All styling is in `styles.css` for easy edits.
- The layout is responsive and lightweight.
