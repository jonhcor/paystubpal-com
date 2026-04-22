# PayStubPal — paystubpal.com

## How to deploy
1. This folder IS your full site repo
2. Add your existing site files here (index.html, paycheck-calculator.html, etc.)
3. Push to GitHub → Cloudflare auto-deploys

## Before uploading — one required edit
Open `ads.txt` and replace `pub-XXXXXXXXXXXXXXXX` with your real AdSense Publisher ID
(Find it in AdSense → Account → Account information)

## File structure
```
paystubpal-com/
├── index.html                              ← ADD: your existing homepage
├── paycheck-calculator.html                ← ADD: your existing file
├── pay-stub-generator.html                 ← ADD: your existing file
├── minimum-wage.html                       ← ADD: your existing file
├── severance-calculator.html               ← ADD: your existing file
├── privacy-policy.html                     ← ADD: your existing file
├── ads.txt                                 ✅ ready (edit pub ID first)
├── robots.txt                              ✅ ready
├── sitemap.xml                             ✅ ready
└── workers-comp-class-code-lookup.html     ✅ ready (new tool)
```

## After deploying to Cloudflare
1. Go to Google Search Console
2. Submit sitemap: https://paystubpal.com/sitemap.xml
3. Use URL Inspection to request indexing on each page individually
