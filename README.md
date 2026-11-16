# PremLabs — Prem Sarojanand

Portfolio of Prem Sarojanand, senior backend engineer (Java, Node.js, Python) building LLM-powered products.

🌐 **https://premlabs.github.io/**

## Pages

- `/` — profile, skills by language, filterable project catalog, contact
- `/projects/juno-health/` — Juno Health case study with an architecture diagram and module catalog
- `/datastructure/` — 13 interactive DSA tutorials (served from the [datastructure](https://github.com/PremLabs/datastructure) repo)
- `404.html` — site-wide not-found page (GitHub Pages uses it for every PremLabs project site)

## SEO files

- `robots.txt` lists both sitemaps
- `sitemap.xml` covers this repo's pages; `/datastructure/sitemap.xml` covers the tutorials
- `llms.txt` summarises the site for AI search tools
- Every page has a canonical URL, Open Graph/Twitter cards and JSON-LD (`ProfilePage` + `Person` on the home page, `Article` on the case study)

**After deploying:** add `https://premlabs.github.io/` to [Google Search Console](https://search.google.com/search-console), submit both sitemaps, and request indexing for the home page and the Juno Health page. Do the same in Bing Webmaster Tools.

## Editing

Plain HTML and one stylesheet (`assets/site.css`), no build step. To add a project, copy an `<li class="item">` in `index.html` and set `data-tags` to any of `java node python ai devops` so the filters pick it up.

## Publishing

Settings → Pages → Deploy from a branch → `main` / root.
