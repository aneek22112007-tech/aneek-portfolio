# Aneek Das — AI Systems & Cloud Portfolio

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Interactive 3D personal engineering portfolio for **Aneek Das** — AI Systems, Agentic Architectures, GRPO Reinforcement Learning, and Cloud-Native Backends.

## 🌟 Key Features

- **Linear/Raycast Design Language**: Dark obsidian aesthetic (`#050508`) with calibrated neon cyan (`#22d3ee`) and electric indigo accents.
- **Dynamic 3D Ambient Canvas**: Built with Three.js — features an interactive cybernetic particle surface wave with harmonic sine wave equations, rotating nested polyhedral cores, and smooth cursor parallax.
- **Cursor Spotlight Lighting**: Radial spotlight borders that track pointer coordinates across cards in real-time.
- **Production Content**:
  - **8 Featured Systems**: Including *MCP Guard*, *Cascade Sentinel*, *Fire Drill*, *Nummuss*, and RL gym environments (*LegalArgue RL*, *SocraticRL*, *InboxZeroEnv*).
  - **Open Source Contributions**: The HPX Project (C++20 parallel computing runtime) merged PR breakdown.
  - **Academic Background & Certifications**: Polaris School of Technology, OCI AI Foundations, IIT Bombay Cybersecurity, and NSO Gold Medal.

## 🚀 Instant Deployment on Render

This repository includes a [`render.yaml`](./render.yaml) blueprint specification for 1-click deployment on [Render](https://render.com):

1. Click the **Deploy to Render** button above, or go to the [Render Dashboard](https://dashboard.render.com).
2. Select **New +** → **Static Site**.
3. Connect this GitHub repository (`aneek22112007-tech/portfolio`).
4. Settings:
   - **Build Command**: *(leave blank)*
   - **Publish Directory**: `.`
5. Click **Create Static Site** — Render will automatically build and assign a global CDN URL (e.g. `https://aneek-das-portfolio.onrender.com`).

## 🛠 Local Development

Because this portfolio is built with zero external build step dependencies, simply open `index.html` in any browser or run a lightweight local server:

```bash
# Python
python3 -m http.server 3000

# Node.js
npx serve .
```

Visit `http://localhost:3000`.

## 📄 License

MIT © [Aneek Das](https://github.com/aneek22112007-tech)
