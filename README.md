# amber.pro.bd — Personal Portfolio

A responsive, accessible personal portfolio for **Md. Ammar Ali Khandoker**.

## What's included

- Responsive single-page portfolio (desktop, tablet and mobile)
- About, expertise, work experience and contact sections
- Lightweight navigation and scroll effects
- SEO metadata, Open Graph tags, sitemap and robots.txt
- Custom-domain file for `amber.pro.bd`
- No framework or build step required

## Run locally

Open `index.html` in a browser, or start a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Keep the custom domain as `amber.pro.bd` in the Pages settings. The repository already includes a `CNAME` file.

## Custom domain DNS

At the DNS provider for `amber.pro.bd`, configure the apex domain records recommended by GitHub Pages. GitHub's current Pages documentation lists the required A/AAAA records and verification guidance:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

DNS changes can take time to propagate. Enable **Enforce HTTPS** in GitHub Pages after the domain has been verified and the certificate is ready.

## Update your profile

Edit `index.html` for text and links, `styles.css` for appearance, and `script.js` for interactions. Review public contact details before adding a phone number or email address.