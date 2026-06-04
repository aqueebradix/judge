# Judge.me × Shopify — .store Domain Prototype

A single-page prototype that recreates the Judge.me Reviews app inside the Shopify admin and adds a domain registration flow for free `.store` domains.

## What's in here

- **Home page** — replicates the Judge.me Reviews dashboard: branded header, setup guide with task progress, and analytics widgets.
- **Setup guide** — the third task ("Setup branded domain") deep-links into the domain registration flow. Dismissing it (or returning from a successful registration) advances the guide to the next task.
- **Domain setup** — lives under Settings. A search hero with `.store` baked in, an exact-match hero result + suggested alternative `.store` names, an inline registration form with consent, and a success screen that walks the user through connecting the new domain inside Shopify settings.

## Running locally

It's a single static HTML file. Open `index.html` in a browser, or serve the directory with any static file server.

## File layout

```
index.html        ← the prototype
judgelogo.png     ← Judge.me icon
shopifylogo.png   ← Shopify wordmark (top bar)
assets/           ← Polaris SVGs used in the page
```
