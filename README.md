# DW8 Solutions website

Static business website for [dw8solutions.com.au](https://dw8solutions.com.au).

## Deploy with Cloudflare Pages

1. In Cloudflare Dashboard, open **Workers & Pages**.
2. Select **Create** → **Pages** → **Connect to Git**.
3. Choose this repository and the `main` branch.
4. For a plain HTML site, leave the build command empty and set the build output directory to `/` (the repository root).
5. Deploy. Cloudflare Pages will provide a `pages.dev` preview URL.
6. In the Pages project's **Custom domains**, add `dw8solutions.com.au`.

## Domain and email DNS

When configuring the root domain, Cloudflare may ask you to move the domain's nameservers to Cloudflare. Before changing nameservers, copy and recreate all existing DNS records, especially MX, SPF and DKIM records, so email continues to work.

## Local preview

Open `index.html` in a browser. No build step or JavaScript framework is required.

## Customise

Update the copy, contact email, and styling in `index.html` before publishing if needed.
