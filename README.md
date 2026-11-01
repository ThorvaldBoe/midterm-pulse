# Midterm Pulse

A fast, pure front-end election market showcase for the 2026 US midterms. It reads active market data from Polymarket's public Gamma API in the visitor's browser. No server, API key, build step, or framework is required.

## Run locally

Open `index.html` in a browser, or serve the directory with any static file server. The market API requires an internet connection and may be subject to browser CORS or API availability.

## Publish with GitHub Pages

1. Create a public GitHub repository and add these files to its root.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. GitHub Pages will serve `index.html` at the repository URL.

## Data and scope

The page queries Polymarket's public Gamma API from the browser. Market titles and availability can change, and the feed gracefully reports when matching markets are not available. Prices are presented as implied probabilities, not as guarantees or advice. The project is an independent visualization and is not affiliated with Polymarket.

## License

MIT. See [LICENSE](LICENSE).
