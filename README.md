# FreshCatch Wholesale

A lightweight, mobile-friendly B2B seafood marketplace prototype for restaurants, retailers, hotels and caterers.

## Features

- Seafood product catalogue
- Search and category filters
- Price per kilogram
- Minimum wholesale quantity of 10 kg
- Automatic bulk pricing tiers
- Stock visibility
- Shopping cart and estimated totals
- Responsive single-page interface
- Demo checkout flow

## Pricing demo

- 10-24 kg: standard price
- 25-49 kg: 5% discount
- 50+ kg: 10% discount

## Run locally

No build step or dependencies are required. Open `index.html` in a modern browser.

For a local web server, you can also use any static-file server of your choice.

## Project structure

```text
freshcatch-wholesale/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Publish to GitHub

After authenticating GitHub CLI:

```bash
git init -b main
git add .
git commit -m "Initial FreshCatch wholesale marketplace"
gh repo create freshcatch-wholesale --public --source=. --remote=origin --push
```

## Production roadmap

This repository is an MVP prototype. A production version should add:

- Buyer and administrator authentication
- PostgreSQL/Supabase or equivalent persistent database
- Server-side inventory and pricing controls
- Customer-specific wholesale pricing
- Persistent orders and order status
- Product image storage
- Payment provider integration
- Invoices and applicable tax handling
- Delivery slots and fulfilment tracking
- Notifications
- Audit logging, validation and security controls

## Important

The included products, prices, stock and checkout process are demo data only. Verify all applicable food-business, import/export, payment, privacy and tax requirements before production use.

## License

MIT License. See `LICENSE`.
