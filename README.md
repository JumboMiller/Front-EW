# Elemental Wars — Official Web App

Landing page and web frontend for [Elemental Wars](https://wax.atomichub.io/explorer/collection/elementalwar) — a play-to-earn NFT game built on the WAX blockchain.

Built for players and collectors who want to explore the game, learn about the EWARS token, and access the NFT marketplace.

---

## Features

- Single-page marketing site for the Elemental Wars game
- Interactive element selector (Fire, Water, Earth, Air) with animated mage previews
- Sections for game lore: Magic, Lands, Token, Tokenomics, Pre-sale
- Direct link to the AtomicHub NFT collection
- Responsive layout using Bootstrap 5
- WAX wallet integration libraries included (`@waxio/waxjs`, `anchor-link`)

---

## Tech Stack

| Layer        | Library / Tool                        |
|--------------|---------------------------------------|
| Framework    | React 17                              |
| Routing      | React Router DOM 5                    |
| Styling      | Bootstrap 5, Animate.css, custom CSS  |
| Blockchain   | WAX (`@waxio/waxjs`, `anchor-link`)   |
| HTTP client  | Axios                                 |
| Tooling      | Create React App                      |

---

## Getting Started

### Prerequisites

- Node.js ≥ 14
- npm ≥ 6

### Install

```bash
git clone https://github.com/JumboMiller/Front-EW.git
cd Front-EW
npm install
```

### Run locally

```bash
npm start
```

Opens at [http://localhost:3000](http://localhost:3000). The page hot-reloads on file changes.

---

## Scripts

| Command           | Description                                      |
|-------------------|--------------------------------------------------|
| `npm start`       | Start the development server on port 3000        |
| `npm run build`   | Build the app for production into `build/`       |
| `npm test`        | Run tests in interactive watch mode              |
| `npm run eject`   | Eject CRA config (irreversible)                  |

---

## Project Structure

```
src/
├── App.js          # Router setup — single route renders Home
├── Home.js         # Main page: navbar, element sections, token info, footer
├── App.css         # Global and component-specific styles
├── fonts/          # Custom font files
└── img/            # All image assets (logos, backgrounds, mage sprites, tokens)

public/
└── manifest.json   # PWA manifest (name: "Elemental Wars", short_name: "EWARS")
```

---

## Deployment

Build the static output and deploy to any static hosting provider:

```bash
npm run build
```

The `build/` directory contains the production-ready app. Compatible with Netlify, Vercel, GitHub Pages, or any CDN.

---

## Links

- NFT Collection: [atomichub.io/explorer/collection/elementalwar](https://wax.atomichub.io/explorer/collection/elementalwar)
- Whitepaper: [elementalwarss.gitbook.io/elemental-wars](https://elementalwarss.gitbook.io/elemental-wars/)
- Twitter: [@PlayElementals](https://twitter.com/PlayElementals)
- Telegram: [t.me/elementalwars](https://t.me/elementalwars)
- Medium: [@elementalwarss](https://medium.com/@elementalwarss)

---

## License

This project is private. All rights reserved by ARKAD.  
Contact: elementalwarss@gmail.com
