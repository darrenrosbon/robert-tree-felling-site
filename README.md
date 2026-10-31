# Robert Tree Felling

One page, mobile first website for Robert Tree Felling, a fully insured tree felling business serving Sandton and nearby suburbs.
Static HTML, CSS and a little JavaScript. No build step. Open `index.html` in a browser, or serve the folder with any static server.

Live site (GitHub Pages): https://darrenrosbon.github.io/robert-tree-felling-site/

## Business details

- Phone and WhatsApp: +27 73 130 2202
- Hours: Mon to Sat, 8am to 5pm, closed Sunday
- Area: Sandton, Gauteng, plus Sunninghill, Woodmead, Bryanston, Rivonia, Fourways, Randburg, Morningside, Midrand and Johannesburg
- Services: tree felling, stump uprooting, bush site clearance, tree trimming, palm cleaning, instant lawn
- Fully insured; quotes are free

## What is in the folder

- `index.html`: the whole site, with its styles and scripts inline
- `img/`: photos, logo cut-outs and the link preview image (`og-image.jpg`)
- `favicon.*`, `apple-touch-icon.png`, `icon-*.png`, `site.webmanifest`: icons and install settings
- `sitemap.xml`, `robots.txt`: search engine files
- `404.html`: page shown for unknown addresses

## How the quote form works

The form builds a friendly WhatsApp message from the visitor's name, suburb, chosen services and details, then opens WhatsApp to Robert's number. Nothing is stored or sent to a server.

## When the web address changes

If the site moves to a custom domain, update the address in:

- `index.html`: the canonical link, the `og:url` and `og:image` tags, the `twitter:image` tag, and the structured data near the top
- `sitemap.xml` and `robots.txt`

Then submit the new sitemap in Google Search Console.

## Images

Stock photos come from Pexels. The recent work photos, the review and the flyer details were supplied by the client.
