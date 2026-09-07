# Paolo Perrusi — Portfolio & Project Showcase

A dynamic, automated developer portfolio and project hub deployed on GitHub Pages.

🔗 **Live Portfolio:** [https://paoloperrusi.github.io/](https://paoloperrusi.github.io/)

---

## Features

- ⚡ **Dynamic GitHub REST API Sync:** Automatically pulls public repositories, live GitHub Pages deployments, metadata, stars, and topics using the GitHub Public REST API.
- 🚀 **One-Click Launch:** Direct links to live GitHub Pages web apps alongside repository source code links.
- 🔍 **Real-Time Filtering & Search:** Search by project name, description, primary language, or topics with instant results.
- 🛡️ **Offline & Rate-Limit Resilient:** Features smart `localStorage` caching and fallback data to ensure instant render times and seamless viewing even if GitHub's unauthenticated API rate limits are encountered.
- 🎨 **Modern Dark Cyberpunk / Obsidian Aesthetic:** Built with responsive CSS, glassmorphism cards, glowing ambient gradients, and crisp typography (`Syne`, `Inter`, `JetBrains Mono`).

## How New Projects Are Added

Whenever you deploy a new project to GitHub Pages under your account:
1. Enable GitHub Pages on that repository.
2. The portfolio will automatically discover it on the next page load via the GitHub Public API and render a live card with a direct **Launch App** link!

## Local Development

```bash
git clone https://github.com/paoloperrusi/paoloperrusi.github.io.git
cd paoloperrusi.github.io
# Open index.html in your browser or run:
npx serve .
```

## License

MIT License.
