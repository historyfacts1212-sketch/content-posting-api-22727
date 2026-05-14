# Shorts Pipeline Studio Static Site

This repository contains the public static website for the TikTok Developer Portal submission.

- Terms of Service: `/terms.html/`
- Privacy Policy: `/privacy.html/`
- Official website: `/index.html`

Expected GitHub Pages URLs:

- `https://historyfacts1212-sketch.github.io/content-posting-api-22727/`
- `https://historyfacts1212-sketch.github.io/content-posting-api-22727/terms.html/`
- `https://historyfacts1212-sketch.github.io/content-posting-api-22727/privacy.html/`

These files are not legal advice. Have the policy text reviewed if your app collects personal data, serves users in regulated regions, or supports commercial activity.

## GitHub Pages Setup

The repository has the static site files, but GitHub Pages must be enabled in repository settings:

1. Open repository Settings.
2. Open Pages.
3. Under Build and deployment, choose one of:
   - Source: `Deploy from a branch`, branch `master`, folder `/ (root)`, or
   - Source: `GitHub Actions`, then use the included Pages workflow.
4. Wait for deployment to complete.
5. Verify the URLs above return `200 OK`.

TikTok may require URL ownership verification for the website URL, Terms URL, and Privacy URL. The existing `tiktok*.txt` verification files are preserved at the repository root and inside the policy directories.
