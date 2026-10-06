# kuldeep.co.in

Portfolio of Kuldeep Singh Rathore, DevOps Lead (Platform & MLOps). A single static page styled as a live ops console: an animated cluster view, the EY DigiGST case study, a deploy-log career timeline, a certificate expiry panel and a Ctrl K command menu. No build step; hosted on GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: content, styles and scripts |
| `Kuldeep_Singh_Rathore_Resume.pdf` | Résumé linked from the site |
| `og.png` | Preview image for LinkedIn / WhatsApp shares |
| `CNAME` | Custom domain `kuldeep.co.in` |
| `robots.txt`, `sitemap.xml` | Search engine indexing |
| `.nojekyll` | Serve files as-is |

## DNS (GoDaddy)

- `A @` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME www` → `kuldeep-devops01.github.io`
- Then in Settings → Pages tick **Enforce HTTPS** once the certificate is issued.

## Updating

Edit `index.html` and commit. GitHub Pages redeploys in a minute or two.
