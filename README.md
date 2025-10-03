# Auréliya — Sovereign AI Mockup Console (Single Page)

This repository contains a ready-to-deploy **single-page demo** of your Sovereign AI console. It renders a home **grid of modules** and in-page panels (TrustOS → VC Orchestrator) using a tiny hash router and vanilla JS.

---

## Pages included
| Page | Purpose |
| --- | --- |
| `index.html` | Single-page app with a responsive grid of module cards and in-page panels for each module. |
| (no build tools) | Pure HTML/CSS/JS — perfect for Vercel static hosting. |

### Modules surfaced in the grid
TrustOS · SovereignWealth · MirrorMe · Boardroom Access · Auréliya Air · Quantum Income Router · Legal Advisor · Intake Triage · Lead Router · Scheduler · Proposal Generator · Payments Agent · Contracts & eSign · Reputation & Reviews · Testimonials Writer · Analytics & KPI · Experiments Orchestrator · Compliance & Data Hygiene · Incident & Status · **KB Librarian** · Vendor COI/Docs · **VC Orchestrator** · **Licensing Radar**

---

## Running locally
Open `index.html` in any browser. No dependencies required.

---

## Deploying to Vercel
1. Create a new GitHub repo and add **`index.html`** (and this **`README.md`**) at the root.
2. In Vercel, click **New Project → Import Git Repository** and pick your repo.
3. Framework Preset: **Other** · Root Directory: **/** · Build command: **(none)** · Output: **/**.
4. Deploy. Your URL will serve `index.html` at `/` automatically.

> Tip: To deploy by uploading a ZIP directly, extract the zip first, then drag the folder into the repo on GitHub or use Vercel’s “Import from Git” flow.

---

## Structure
```
/ (repo root)
├─ index.html     # your full single-page mockup (all modules)
└─ README.md      # this guide
```

---

## Accessibility & UX
- Keyboard focus styles and ARIA labels on grid/panels
- Works on mobile (auto-fit grid, sticky header)
- No external fonts or scripts

---

## Legal
These screens are **mockups** only. There is **no backend**; all buttons simply append to a local on-page log for demos.

© Auréliya Holdings
