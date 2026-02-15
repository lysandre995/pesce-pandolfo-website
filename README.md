# Pesce & Pandolfo Wedding Website

Wedding website for Viola Luz Pandolfo and Federico Pesce — June 13, 2026.

Built with [Eleventy](https://www.11ty.dev/), deployed on GitHub Pages.

## Setup

```bash
nvm use
npm install
```

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

Output goes to `_site/`.

## Configuration

- **Site data**: `src/_data/site.json` (names, dates, IBAN, locations, Google Form URL)
- **Gallery**: `src/_data/gallery.json` (photos and videos array)
- **Assets**: `src/assets/images/` (add photos here)

## Deploy

Automatic via GitHub Actions on push to `main`. Requires GitHub Pages source set to "GitHub Actions" in repo settings.

## License

ISC
