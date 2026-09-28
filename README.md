# kuldeep.co.in

Portfolio of Kuldeep Singh Rathore, DevOps and MLOps engineer. A single static page with self-hosted fonts and no build step, hosted on GitHub Pages.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: content, styles, the pipeline diagram and the EY case-study chart |
| `Kuldeep_Singh_Rathore_Resume.pdf` | Resume linked from the site |
| `og.png` | Preview image shown when the link is shared on LinkedIn or WhatsApp |
| `*.woff2` | Archivo and Source Sans 3 fonts, served from the repo |
| `robots.txt`, `sitemap.xml` | Let search engines find and index the page |
| `.nojekyll` | Serves files as they are, without Jekyll processing |

## Point kuldeep.co.in at this site

1. At your DNS provider, replace the current records for `kuldeep.co.in` with four `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
2. Add a `CNAME` record for `www` pointing to `<username>.github.io`.
3. In the repo, open **Settings > Pages**, enter `kuldeep.co.in` as the custom domain and save. GitHub adds a `CNAME` file.
4. When the DNS check passes, tick **Enforce HTTPS**.
5. Remove the old Lovable hosting for the domain.

## Adding finops.kuldeep.co.in

- Static front end only: its own repo with GitHub Pages and custom domain `finops.kuldeep.co.in`, plus a DNS `CNAME` record `finops` pointing to `<username>.github.io`.
- Has a backend or database: keep the code on GitHub and run the app on a small server (for example AWS Lightsail or EC2), with a DNS record for `finops` pointing there.

## Updating

Edit `index.html` and commit. GitHub Pages redeploys in a minute or two.
