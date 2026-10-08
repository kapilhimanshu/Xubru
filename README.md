# Xubru Technologies — GitHub Pages package v2

## Included changes
- Light website is the default; visitors can switch Light / Dark from the top-right control.
- Language selector: English, Marathi, Tamil, Telugu, Bangla, French, Hebrew, Arabic, Chinese and Japanese.
- Hebrew and Arabic switch the layout to RTL automatically.
- The selected theme and language are remembered in the visitor's browser.
- Start a conversation now opens four choices: Xubru.Ai, Lead2, DMSGuru and Perpatual, then preselects the relevant sales route.
- The former hero portfolio diagram has been replaced by a cleaner, compact global portfolio stack.
- Smaller hero typography and improved responsive layout for laptop, tablet and mobile.
- Organization + WebSite + portfolio ItemList schema, canonical, Open Graph, social image, robots.txt and sitemap are included.

## Sales routing
This is a static GitHub Pages site. The current working mail routes in `script.js` are:
- Xubru.Ai → connect@xubru.com
- Lead2 → team@lead2.in
- DMSGuru → connect@xubru.com
- Perpatual → hr@perpatual.com

When you have dedicated named salesperson emails, change only the `SALES_ROUTES` object in `script.js`.

## Multilingual SEO
The language selector is currently a visitor-experience layer on one canonical page. This avoids creating duplicate indexed pages. If you later want the translated versions to rank independently, create real URLs such as `/fr/`, `/ar/`, `/ja/` and only then add reciprocal `hreflang` tags.

## GitHub Pages upload
Upload all files in this folder to the repository root. Keep `CNAME` if `xubru.com` is the preferred custom domain.

Test after deployment:
- https://xubru.com/
- https://xubru.com/robots.txt
- https://xubru.com/sitemap.xml
- https://xubru.com/privacy.html
- https://xubru.com/og-image.png

## Form
The included form works without a backend by opening the visitor's email application with the selected sales route. For reliable production lead capture, connect it to Web3Forms, Formspree, your CRM or your own API and update the privacy notice accordingly.
