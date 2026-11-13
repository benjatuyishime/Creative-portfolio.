# Benjamin Tuyishime — Portfolio

A responsive, clean and minimal portfolio for a Rwandan digital artist, illustrator and creative based in Kigali. Built with plain HTML, CSS and JavaScript for static hosting on Vercel.

## Files
- `index.html` — page content, SEO metadata and portfolio sections
- `style.css` — visual design, layout, responsive styles and accessibility states
- `script.js` — mobile navigation and current year
- `vercel.json` — baseline browser security headers for Vercel deployments

## Before publishing
1. Replace the temporary graphic panels in the Work section with your real illustrations, children's book pages, posters, animation stills, merchandise and social media work. Do not present the temporary panels as completed projects.
2. Add your professional email address and real social profile URLs in the Contact section.
3. Review the About copy and project descriptions for accuracy.
4. Test the site on a phone and desktop, and check the browser console for errors.

## Local preview
Open `index.html` in a browser, or run a local static server from this folder.

## Deploy to Vercel
Commit and push all files, including `vercel.json`, to the GitHub repository connected to Vercel. Vercel will automatically build and deploy the static site. No build command is required; the output directory is `.`.

## Security notes
`vercel.json` adds baseline security headers: content-type protection, referrer policy, a restrictive permissions policy, clickjacking protection and a Content Security Policy. The current policy permits Google Fonts and HTTPS images. If you later add video embeds, analytics, forms or other third-party services, review and update the policy deliberately rather than disabling it. Never put private API keys, passwords or access tokens in frontend files or a public repository.
