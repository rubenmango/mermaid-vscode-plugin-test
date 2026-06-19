# Mermaid Sync — PR Review · Project Hub

Living documentation and weekly metrics for the **Mermaid Diagram Sync / PR Review** feature of the Mermaid Chart VS Code extension.

## 🔗 Live links (GitHub Pages)

| Page | URL |
|------|-----|
| **Project hub** (start here) | https://rubenmango.github.io/mermaid-vscode-plugin-test/ |
| **Project documentation** | https://rubenmango.github.io/mermaid-vscode-plugin-test/docs/mermaid-sync-pr-review.html |
| **Plugins metrics dashboard** | https://rubenmango.github.io/mermaid-vscode-plugin-test/docs/metrics-dashboard.html |

> **One-time setup:** GitHub Pages must be turned on for these links to go live.
> Go to **Settings → Pages → Build and deployment → Source: _Deploy from a branch_**, pick **`main`** and **`/ (root)`**, and Save. The site appears at the hub URL above within a minute or two.

## What's here

- **`index.html`** — the hub: preview cards linking to the documentation and the dashboard.
- **`docs/mermaid-sync-pr-review.html`** — the living project doc: the trust gap, the thesis, the slice roadmap (June re-cut), the login-gate decision, the adoption signal, key decisions, and the build state. Embedded Mermaid diagrams.
- **`docs/metrics-dashboard.html`** — the weekly Plugins metrics snapshot (Mixpanel EU project 2954792): git bot regenerations, VS Code command reach, activation health, and new-feature instrumentation.

## How the dashboard stays current

A scheduled weekly task pulls the locked metric spec from Mixpanel, regenerates `docs/metrics-dashboard.html`, and commits it to this repo — so the hub always shows the latest run.

---

Product Designer — Ruben Mangorrinha · Mermaid Chart Plugins · last updated 2026‑06‑19
