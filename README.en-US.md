# Website Screenshot

Capture websites, HTML, and mobile pages as **JPG, PNG, WebP, or PDF**.

Website Screenshot is a multilingual screenshot and export tool built for people who need to turn live web pages or HTML into images and documents quickly. It supports **website screenshot**, **HTML screenshot**, **iPhone screenshot**, **Android screenshot**, **full page screenshot**, **website to PDF**, and **HTML to PDF** workflows in one product.

## Why People Use It

- Capture a live website URL as JPG, PNG, WebP, or PDF
- Generate full page screenshots for long landing pages and product pages
- Preview websites in iPhone and Android screen sizes
- Export HTML and CSS as image assets or PDF documents
- Save visual QA evidence, client review assets, and internal documentation

## Main Pages

- `website-screenshot`: capture a website URL as JPG, PNG, WebP, or PDF
- `html-screenshot`: turn HTML and CSS into image output
- `iphone-screenshot`: preview a page in popular iPhone sizes
- `android-screenshot`: preview a page in popular Android phone sizes
- `full-page-screenshot`: capture the full page, not just the first viewport
- `website-to-pdf`: save a website as PDF
- `html-to-pdf`: render HTML and CSS as PDF
- `website-full-page-screenshot`: save long desktop pages from top to bottom
- `iphone-full-page-screenshot`: capture long mobile pages in iPhone sizes
- `android-full-page-screenshot`: capture long mobile pages in Android sizes

## What Makes It Useful

- Multiple export formats in one place
- Full-page capture for long pages
- Popular mobile device presets
- Multilingual landing pages and UI
- API-ready architecture for automation workflows

## Supported Languages

- English
- Chinese (Simplified)
- Japanese
- German
- Korean
- French
- Portuguese (Brazil)
- Arabic
- Russian
- Malay

## Built For Real User Tasks

This project is designed for:

- designers reviewing responsive layouts
- QA teams checking sticky headers, CTAs, and long pages
- marketers saving landing pages and campaign previews
- agencies preparing client review files
- product teams documenting visual changes
- developers rendering HTML templates and components

## Local Development

```bash
pnpm install
pnpm run build
PORT=3021 pnpm start
```

Open:

- `http://localhost:3021`

## Environment Notes

Typical environment values include:

- `HTML2IMAGE_API_BASE`
- `HTML2IMAGE_API_KEY`
- `NEXT_PUBLIC_HTML2IMAGE_API_BASE`
- `SITE_DOMAIN`
- `DEFAULT_FORMAT`

The frontend can proxy requests to an upstream HTML-to-image API service.

## API Support

This repository includes support for:

- screenshot jobs
- HTML rendering jobs
- device presets
- full-page capture
- PDF export
- job polling

See:

- [API_USAGE.md](/Users/ericwu/MinibuddyFolder/WebSite/40%20htmtoimage/htmltoimage-showcase/API_USAGE.md)

## SEO Focus

This repository is not only a tool UI. It is also structured as a multilingual SEO project with dedicated landing pages for:

- website screenshot
- webpage screenshot
- URL to image
- HTML to image
- HTML to PDF
- iPhone screenshot
- Android screenshot
- full page screenshot
- long webpage screenshot
- mobile full page screenshot

## Who This README Is For

This README is written for:

- people discovering the project on GitHub
- users searching for website screenshot tools
- developers who want to run the project locally
- partners evaluating the product or API workflow

## License / Usage

Check the repository settings and deployment environment before publishing or redistributing production API credentials.
