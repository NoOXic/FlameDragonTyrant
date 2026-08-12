# Flamedragon Tyrant — Kingshot Alliance Field Manual

A fan-made planning site for **Flamedragon Tyrant**, the cross-kingdom battlefield event in the mobile game [Kingshot](https://www.centurygames.com/). Built for R4/R5 alliance leadership: event timeline, battlefield map, Aerie buffs, the crystal economy, and a full order-of-battle plan for a single qualified alliance.

**Live site:** enable GitHub Pages (see below) and it will be published at
`https://nooxic.github.io/FlameDragonTyrant/`

## Pages

| File | What it is |
|---|---|
| [`index.html`](index.html) | Landing page — the five core rules, the battlefield at a glance, and links into the full manual. |
| [`manual.html`](manual.html) | The full 16-section field manual: timeline, roster construction, the battlefield map, Aerie mechanics, crystal economy and skills, the battle clock, the battle plan, rewards, and the pre-battle checklist. |
| [`styles.css`](styles.css) | Shared design system for both pages. |
| [`img/`](img) | Official in-game screenshots (map, Aerie descriptions, Crystal Skills panel, Champion's Eve) used as reference exhibits throughout the manual. |

## Running it locally

No build step — it's static HTML/CSS. Just open `index.html` in a browser, or serve the folder with anything simple:

```bash
npx serve .
```

## Deploying with GitHub Pages

1. Push this repo to GitHub (`main` branch).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — GitHub publishes the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Disclaimer

Unofficial fan project. Not affiliated with or endorsed by Century Games. Diagrams are original; in-game screenshots in `img/` are Century Games' copyrighted material, reproduced here for reference/briefing purposes only. Verify all timers, costs and figures in-game before D-Day — event details shift between rollouts.
