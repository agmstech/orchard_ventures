# 🌳 Orchard Ventures

**Business ventures, gamified.** Turn your business ideas into a 3D orchard — every venture is a fruit tree you grow from seed to harvest.

Plant a seed for each idea, tick off the milestones it needs to grow, then harvest the fruit as sales roll in. Track money and time in an investment journal, and watch your most profitable venture earn a golden crown.

It's a single self-contained HTML file — no build step, no server, no install. Just open it in a browser.

## ✨ Features

- **3D orchard (Three.js / WebGL)** — real ground and shadows; trees grow through life stages from seed → sprout → tree → fruiting.
- **Ventures as trees** — each tree is one business, chosen from 20 Philippine fruit species (figures shown in pesos, ₱).
- **Milestone-driven growth** — define the requirements a venture needs (funding, development, marketing…), tick them to grow the tree, and drag the handle to reorder them.
- **Harvest = sales** — set how many fruits a venture yields and the value of each; tap a fruit to "sell" it.
- **Investment journal** — log money and time as separate dated entries; add, edit, or delete any line. Totals flow straight into profit and ROI.
- **Profit leaderboard** — ventures ranked live by net profit, ROI, or sales, with a golden crown on the leader.
- **Living scene** — a sun that follows the time of day with a full day → night cycle, drifting clouds, flying birds, and random wind or rain.
- **Full camera control** — orbit, zoom, and rotate the garden on the X, Y, and Z axes; add or remove plots freely.
- **Saved locally** — your orchard persists in the browser, with one-click JSON backup and restore.

## 🚀 Getting started

1. Download `orchard-3d.html`.
2. Open it in any modern browser (Chrome, Edge, Firefox, or Safari).

That's it — there's nothing to install.

### Host it free on GitHub Pages

1. Rename `orchard-3d.html` to `index.html`.
2. Push it to your repository.
3. Go to **Settings → Pages** and set the source to your main branch.
4. Your orchard goes live at `https://<your-username>.github.io/orchard-ventures/`.

## 🛠 Built with

- Vanilla HTML, CSS, and JavaScript — no framework
- [Three.js](https://threejs.org/) r128, bundled into the file so it works offline
- Google Fonts: Fraunces and Spline Sans

## 🔒 Privacy

Everything stays on your device. No account, no server, no tracking. Your data lives in the browser's `localStorage`; use the in-app **Backup** and **Restore** buttons to move it between machines.

> Note: local saving works when you open the file directly or through a hosted page. Some sandboxed preview frames block `localStorage` — that's the frame, not a bug.

## 📁 Files

- `orchard-3d.html` — the main 3D app.

## 📄 License

Released under the MIT License — free to use, modify, and share.
