# Carajillo

A beautiful static site celebrating the carajillo cocktail.

## Deploy to Vercel

1. Push this repo to GitHub
2. Import the repo in [Vercel](https://vercel.com/new)
3. Enable Analytics in the project
4. Copy the Analytics script path from Vercel's HTML quickstart
5. Set the `data-va-script` attribute on the root `<html>` tag in `index.html`
6. Deploy

Or use the Vercel CLI:

```bash
npm i -g vercel
vercel
```

## Vercel Analytics

This site includes the Vercel Analytics bootstrap function and a safe loader for the HTML integration.

To finish setup, replace the empty `data-va-script=""` in `index.html` with the project-specific path Vercel gives you in the Analytics quickstart, then redeploy.

## Local Development

Just open `index.html` in your browser, or use a local server:

```bash
npx serve .
```

## About

The carajillo is a Spanish coffee cocktail made with espresso and Licor 43. Simple, delicious, timeless.
