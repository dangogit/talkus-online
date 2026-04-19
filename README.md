# talkus.online

Personal landing page for Jovie Vecinal, freelance customer service representative.

## Stack
- Static HTML + Tailwind (via CDN)
- Google Fonts: Inter, Plus Jakarta Sans, Caveat
- Hosted on GitHub Pages
- Custom domain: talkus.online

## Local preview
Open `index.html` directly in a browser, or:
```bash
python3 -m http.server 8000
```

## Deploy
Pushed to `main` triggers GitHub Pages redeploy automatically.

## DNS setup (one-time)
For apex `talkus.online`, add these A records at your DNS provider:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

For `www.talkus.online`, add a CNAME pointing to `<username>.github.io`.
