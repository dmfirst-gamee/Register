# DMFirst Game Guide

Responsive static informational website built with HTML, CSS, and vanilla JavaScript. This site is not represented as the official DMFirst platform.

## Deploy on Netlify
1. Import this GitHub repository into Netlify.
2. Set environment variable `SITE_URL` to your final HTTPS domain (for example, `https://example.com`).
3. Build command: `node scripts/generate-seo.js`.
4. Publish directory: `.`.
5. Deploy and check `/robots.txt`, `/sitemap.xml`, and canonical URLs.
6. Submit the sitemap in Google Search Console.

The build script intentionally stops if `SITE_URL` is missing rather than publish placeholder canonical URLs. Conversion links open the specified registration destination. The site does not collect credentials.