# Tablecraft

Turn CSV into clean Markdown, HTML, or tab-separated tables. Preview the result before copying it into a README, issue, document, or spreadsheet.

**Live demo:** [Try Tablecraft](https://codearcade-ctrl.github.io/tablecraft/)

**Languages:** [English](README.md) | [Nederlands](README.nl.md)

## Features

- Parses quoted fields, escaped quotes, and embedded commas
- Exports Markdown, HTML, and TSV
- Choose a comma, semicolon, or tab delimiter
- Toggle whether the first row is a header
- Safe HTML escaping and a text-only table preview
- Runs locally with no dependencies or uploads

## Use it

Open `index.html`, paste CSV, choose its delimiter, then select **Convert**. Switch output formats at any time. The page works offline.

## Publish with GitHub Pages

Push to the `main` branch. The included GitHub Actions workflow publishes the site to GitHub Pages. In repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions** if it is not selected automatically.

## License

MIT. See [LICENSE](LICENSE).
