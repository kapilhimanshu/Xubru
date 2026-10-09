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

## Multilingual SEO
The language selector is currently a visitor-experience layer on one canonical page. This avoids creating duplicate indexed pages. If you later want the translated versions to rank independently, create real URLs such as `/fr/`, `/ar/`, `/ja/` and only then add reciprocal `hreflang` tags.

## Xubru logo 
The idea: a solid block cut by an X. The mark is one solid rounded square sliced by an X-shaped gap. The X is the empty space, and the four pieces are what remain. It is a single shape with no icons, dots or gradients, and it is still readable at favicon size or stamped in one color.
The story: “Four platforms, one company, and the X where they meet.”
The block is Xubru Technologies, one solid company.
The four pieces are the four platforms: Xubru.Ai, Lead2, DMSGuru and Perpatual. Each is a distinct specialist, but only because the whole was cut along the X.
The X is the shared intelligent core that connects them. It is the only part not filled in, which fits “AI in the operating layer.”
The rounded corners keep it human and approachable, matching the “human-centred” line on your site.
Two versions:
Mono navy is the primary logo for the site, invoices, stamps and favicons. Apple-style brands lead with one color, and it holds up on any background.
Four-tint blue gives each piece its own shade, for decks and brand pages. It also lets each product use the same mark with its own piece highlighted.
Files:
SVG logos: xubru-final-logo-mono.svg and xubru-final-logo-color.svg are the scalable masters.
PNG logos: xubru-final-logo-mono-4000.png and xubru-final-logo-color-4000.png have transparent backgrounds.
Icons: xubru-final-icon-mono-2048.png and xubru-final-icon-color-2048.png are the mark alone, for app icons and profile pictures.
The wordmark still uses a stand-in font (DejaVu Sans Bold). A global brand would normally have a custom or carefully chosen typeface, so I’d treat that as the next step. I can try a lighter, more refined wordmark, or a dark-background version.






## Form
The included form works without a backend by opening the visitor's email application with the selected sales route. For reliable production lead capture, connect it to Web3Forms, Formspree, your CRM or your own API and update the privacy notice accordingly.
