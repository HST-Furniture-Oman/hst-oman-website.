# HST Oman — Website

Responsive bilingual (English/Arabic) static website for HST, Al Amarat, Oman.

## Included
- `index.html`: page structure, SEO metadata and LocalBusiness structured data
- `styles.css`: responsive traditional-inspired styling
- `script.js`: language switch, mobile menu and WhatsApp enquiry form
- `assets/favicon.svg`: HST icon
- `robots.txt` and `sitemap.xml`: starter crawler files

## Deploy free with Cloudflare Pages
1. Visit https://github.com/new and create a repository, for example `hst-oman-website`.
2. Upload the *contents* of this folder to the repository root. Make sure `index.html` is directly in the root, not nested inside another folder.
3. Sign in at https://dash.cloudflare.com/.
4. Open **Workers & Pages** → **Create** → **Pages** → **Connect to Git** (labels may vary slightly).
5. Connect GitHub and select your repository.
6. Use **None** as framework preset. No build command is needed. Set the output directory to `/` or `.` as the dashboard accepts.
7. Deploy. Cloudflare will assign a free address similar to `https://your-project.pages.dev`; exact names depend on availability.
8. Test the site on desktop and mobile. Check both languages and submit a test enquiry to confirm WhatsApp opens.
9. Future commits to the connected branch trigger automatic redeployment.

If Cloudflare's current dashboard offers direct upload for Pages, you can upload the files directly instead; otherwise use the Git connection workflow above.

## Before launch
- Replace the illustrative stock photos with your own completed-work photos where possible. Current images are remote Unsplash examples and are not verified HST projects.
- Confirm all service descriptions, phone number and location are correct.
- The contact form does not store submissions; it creates a WhatsApp message.
- After deployment, replace `YOUR-PROJECT.pages.dev` in `robots.txt` and `sitemap.xml` with your real assigned domain.

## Google Search Console
1. Open https://search.google.com/search-console/ and add the deployed URL as a URL-prefix property.
2. Complete the verification method offered by Google.
3. Submit `https://YOUR-PROJECT.pages.dev/sitemap.xml` after replacing the placeholder with the actual domain.
4. Indexing can take time and is not guaranteed. This website does not automatically resolve Google Business Profile/Maps visibility issues; manage that profile separately.

## Cost
The site uses static files and can be hosted on Cloudflare Pages' free offering. A `pages.dev` address is free; a custom domain such as `.com` is optional and usually costs money. Fonts and sample photos load from third-party services and require internet access.
