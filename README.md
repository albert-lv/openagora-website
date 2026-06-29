# openagora-website

> Marketing website for [OpenAgora](https://github.com/albert-lv/OpenAgora) — an open-source rollout, verification, and trajectory plane for agentic reinforcement learning.

**Live site:** https://albert-lv.github.io/openagora-website

---

## What's This?

A static landing page that showcases **Arena** (OpenAgora) — the missing infrastructure layer between RL trainers and agent execution environments.

The site highlights:

- **Four Composable Planes** — Rollout Control, Sandbox, Verification, and Trajectory Data
- **End-to-End Demos** — Code Colosseum (GRPO live training), Relationship Chat RL (PPO on CPU), SWE-Agent, veRL integration
- **Architecture & Comparison** — why Arena stands apart from ROCK, LiteLLM, E2B, and SWE-Gym
- **Quick Start** — get a rollout running in under 5 minutes

---

## Tech Stack

| Tech | Purpose |
|------|---------|
| Static HTML5 | Single-page marketing site |
| Vanilla CSS | No build step, no dependencies |
| Google Fonts (Inter, JetBrains Mono) | Typography |
| GitHub Pages | Hosting |

---

## Development

No build tools required. Just open `index.html` in a browser:

```bash
# macOS
open index.html

# or serve locally
python3 -m http.server 8080
# open http://localhost:8080
```

---

## Deploy

Pushed to `main` branch auto-deploys via **GitHub Pages**.

```bash
git add -A
git commit -m "feat: update landing page"
git push origin main
```

---

## Project Structure

```
openagora-website/
├── index.html          # Landing page
├── styles.css          # All styles (dark theme)
├── images/             # Screenshots & assets
└── README.md           # This file
```

---

## License

Same as [OpenAgora](https://github.com/albert-lv/OpenAgora) — [Apache 2.0](https://opensource.org/licenses/Apache-2.0)
