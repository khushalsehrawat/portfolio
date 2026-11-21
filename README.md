# portfolio


🌐 Visit my web development studio — [TheVB24.com](https://www.thevb24.com)


## Website metadata

The two static HTML pages preserve their existing titles, personal branding, artwork and application code. Both include descriptions, Khushal Sehrawat as author, TheBenzzCreations as creator, Open Graph metadata and Twitter card metadata.

Production identity is recorded in `seo-sites.json`; see Canonical URL validation below. The developer credit is not evidence of a project deployment URL.

The existing TheVB24 studio link above is retained. No social preview image is configured. Structured data does not guarantee search rich results.

This is a static HTML/CSS/JavaScript project using Bootstrap and jQuery from CDNs. Serve the repository with a static web server to preview it. No package manifest, configured lint suite or build command is present.

## Development & Maintenance

**Developed & Maintained by
[Khushal Sehrawat](https://github.com/khushalsehrawat)**
— Founder of
[TheBenzzCreations](https://www.thebenzzcreations.com/).

TheBenzzCreations is a digital development studio specializing in website development, custom software, mobile applications, e-commerce solutions and AI-powered business automation.

For development enquiries and collaborations, visit [TheBenzzCreations](https://www.thebenzzcreations.com/).

## Canonical URL validation

Run `python scripts/validate_seo.py` from this repository before publishing. The dependency-free check validates exact page canonicals, Open Graph URLs, website/application JSON-LD URLs, sitemap locations, robots sitemap references and literal framework site metadata against `seo-sites.json`. It checks deployment path prefixes as well as domains, so one GitHub Pages project cannot canonicalize to another.

Only URLs whose live HTML matched the local page on 2026-11-21 are configured. Unverified pages have no canonical or social URL; `python scripts/validate_seo.py --require-verified` also fails for those pending pages. Reverify the configuration if the deployment moves. Dynamic framework expressions still require runtime validation.

TheBenzzCreations attribution, creator organization URLs and existing normal same-tab developer credit links are preserved. These outbound attribution links are separate from site identity.
