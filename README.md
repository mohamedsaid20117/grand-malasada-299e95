# Smart Tools Hub (أدواتي الذكية) — Netlify Deployment Package

## Project Structure
- `index.html` — Complete single-page application (HTML5, Tailwind CSS CDN, Vanilla JavaScript).
- `netlify.toml` & `_redirects` — Netlify routing, headers, and build configuration.
- `package.json` — Project metadata and build script compatibility for Git-based CI/CD.
- `ads.txt` — Google AdSense authorized digital sellers file (replace `pub-1234567890123456` with your own AdSense Publisher ID).
- `robots.txt` & `sitemap.xml` — Search engine and `Mediapartners-Google` crawler configuration.

## How to Deploy on Netlify
### Method 1: Drag & Drop (Fastest)
1. Go to https://app.netlify.com/drop
2. Drag and drop either the unzipped project folder or `smart-tools-netlify-deploy.zip` directly onto the page.

### Method 2: Git Repository (GitHub / GitLab / Bitbucket)
- **Build command:** Leave blank (or `npm run build`)
- **Publish directory:** `.` (root directory)
