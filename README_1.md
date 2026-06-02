# MOBIN · QA Portfolio + Framework Engine

Two static pages, modeled on the reference sites but rebuilt with a **trading-terminal**
aesthetic and your own work (MultiBank QA — Appium/Java mobile, RestAssured/TestNG API
framework migration, n8n smoke/regression, Qase/Jenkins/Jira).

## Files
- `index.html` — main portfolio (hero, impact, experience, lab, live test simulator, test
  generator console, execution dashboard, contact)
- `framework-generator.html` — "Framework Engine" 5-step wizard that scaffolds a test-automation
  blueprint (engine → language → build → pattern → CI). Linked from the nav.

Everything is self-contained (only Google Fonts + Chart.js via CDN). No build step, no backend.

## Deploy to GitHub Pages
1. Create a repo (e.g. `qa-portfolio`) on github.com/mobink.
2. Add both files to the repo root.
3. Repo **Settings → Pages → Source: main branch / root** → Save.
4. Live at `https://mobink.github.io/qa-portfolio/`.

## Edit before publishing — search & replace these
| Placeholder | Where | Replace with |
|---|---|---|
| `your.email@example.com` | nav, contact, hero | your real email |
| `YOUR-LINKEDIN` | hero + contact | your LinkedIn handle |
| `+971 00 000 0000` | contact | your phone (or delete the card) |
| `XX%` / `X+` (amber) | Impact section | your verified numbers |
| `[ Previous Company ]` block | Experience | earlier roles, or delete |
| "Dubai, UAE" | hero | your location if different |

The amber `XX%`/`X+` values are intentionally placeholders so nothing unverified ships as fact.
The 145-tests / 10-suites / 160+-cases figures come straight from your actual work.
