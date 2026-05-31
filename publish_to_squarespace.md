# Publish QuoteOps To Squarespace

The site files are ready locally:

- `site/index.html`
- `site/styles.css`
- `site/assets/quoteops-freight-dashboard-hero.png`

Squarespace is currently serving the default "Coming Soon" page for `getquoteops.com`.

## Fastest Builder Version

Use the copy from:

- `getquoteops_landing_page_copy.md`

Create these sections:

1. Hero
2. What it does
3. Offers
4. Who it helps
5. How it works
6. Contact

Upload:

```txt
site/assets/quoteops-freight-dashboard-hero.png
```

Use it as the hero image/background.

## Custom Code Version

If your Squarespace plan supports custom code:

1. Upload `site/assets/quoteops-freight-dashboard-hero.png` to Squarespace.
2. Copy the uploaded image URL.
3. Open `site/squarespace-custom-css.css`.
4. Replace:

```txt
REPLACE_WITH_UPLOADED_HERO_IMAGE_URL
```

with the uploaded image URL.

5. Add the CSS in Design -> Custom CSS.
6. Add the HTML from `site/squarespace-custom-code.html` to a page Code Block.

## Minimum Publish Version

If you only want to get credible fast:

1. Change the default parking page title to:

```txt
QuoteOps
```

2. Change the message to:

```txt
Freight document trackers for billing-ready loads.

We help small freight teams turn PODs, BOLs, invoices, rate confirmations, and carrier docs into one simple view of what is missing, ready, and waiting on follow-up.

Email Iliya: iliya@getquoteops.com
```

This is enough to start the first two outreach emails.
