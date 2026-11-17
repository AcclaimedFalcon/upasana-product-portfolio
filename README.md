# Upasana Mishra — Portfolio Website

A responsive static portfolio website built with HTML and CSS. It is ready to deploy on Cloudflare Pages.

## Files
- `index.html` — portfolio homepage
- `styles.css` — responsive styles
- `projects/sakhi.html` — Sakhi case study
- `assets/sakhi-cover.png` — generated Sakhi cover image

## Preview locally
Open `index.html` in a browser. No build step or package installation is required.

## Deploy to Cloudflare Pages (free)
1. Create a free account at https://dash.cloudflare.com/
2. In Cloudflare, open **Workers & Pages** → **Create** → **Pages**.
3. Choose **Upload assets** / **Direct Upload** (the exact label may vary).
4. Upload the contents of this folder (not just the ZIP file), preserving the `assets/` and `projects/` folders.
5. Choose a project name such as `upasana-portfolio`.
6. Deploy. Cloudflare will provide a `*.pages.dev` public URL.

If the dashboard offers Git integration instead, create a GitHub repository, upload these files, then connect that repository to Cloudflare Pages. For a plain static HTML site, use no framework, no build command, and set the output directory to `/` (or the repository root).

## Update content
Edit `index.html`, `projects/sakhi.html`, or `styles.css`, then redeploy the updated files.

## Notes
- No phone number or resume link is included.
- Contact email: mdrupasana@gmail.com
- LinkedIn: https://www.linkedin.com/in/upasana-m-544467342
- Case-study detail pages for Calm, medicine delivery, Tata 1mg and healthy eating currently link to the corresponding Notion pages.
- The homepage intentionally omits a standalone product philosophy section.
- Replace any wording or claims that do not match the final shipped product before public launch.
