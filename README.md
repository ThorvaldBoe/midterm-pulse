# Midterm Pulse

A fast, pure front-end election market showcase for the 2026 US midterms. It reads active market data from Polymarket's public Gamma API in the visitor's browser. No server, API key, build step, or framework is required.

## Run locally

Open `index.html` in a browser, or serve the directory with any static file server. The market API requires an internet connection and may be subject to browser CORS or API availability.

## Publish with GitHub Pages

1. Create a public GitHub repository and add these files to its root.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. GitHub Pages will serve `index.html` at the repository URL.

## Data and scope

The page reads election forecast data from Polymarket's public Gamma API in the browser. It also reads Google News RSS headlines through the public AllOrigins CORS proxy and refreshes them every ten minutes. Market titles and availability can change; forecasts are not guarantees or advice. News availability depends on Google News and the proxy. This is an independent visualization.

## License

MIT. See [LICENSE](LICENSE).
