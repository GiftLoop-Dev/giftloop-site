# GiftLoop Landing Page

Static landing page for GiftLoop - Shopify app for automated gift reminders.

## Live Site
- Landing: https://giftloop.app
- App: https://app.giftloop.app

## Local Development
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Deployment
Deployed to Vercel:
```bash
vercel --prod
```

## Architecture
- **Landing Site** (this repo): Static HTML at giftloop.app
- **Shopify App**: Remix app at app.giftloop.app
- **Auth Flow**: Landing form → app.giftloop.app/auth → Shopify OAuth → Dashboard