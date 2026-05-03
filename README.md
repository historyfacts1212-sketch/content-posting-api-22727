# TikTok Policy URL Static Site

This folder contains a small static website you can publish to create the URLs TikTok asks for:

- Terms of Service: `/terms.html`
- Privacy Policy: `/privacy.html`
- Official website: `/index.html`

Before publishing, replace every placeholder:

- `Content Posting API 22727`
- `historyfacts1212@gmail.com`
- The app/service description on `index.html`
- Any privacy or terms language that does not match how your app actually works

These files are not legal advice. Have the policy text reviewed if your app collects personal data, serves users in regulated regions, or supports commercial activity.

## Deploy Options

Any static host will work, as long as the pages are public HTTPS URLs. Common choices:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel

After deployment, submit full URLs like:

- `https://your-domain.example/terms.html`
- `https://your-domain.example/privacy.html`

TikTok may require URL ownership verification for the website URL, Terms URL, and Privacy URL.
