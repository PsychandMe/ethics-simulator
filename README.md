# Ethics Simulator

A free, private, in-browser **research-ethics decision game**: you play the researcher,
and at each decision point of a study the ethics committee responds to your call.

**By Joshua Bellot · [Psych & Me](https://substack.com/@psychandme)**

## Why it's different

- **You decide, you live with it** — not a quiz with right answers, but a simulation:
  every choice has an ethical cost or a payoff, and the committee's verdict lands at
  the end of the scenario.
- **Feedback grounded in real frameworks** — the BPS Code of Human Research Ethics
  (2022), UK GDPR practice, and safeguarding conventions.
- **Built for reflection, not scoring** — the exportable report puts your choices
  beside the model answers with prompts for seminars and supervision.
- **Private by design** — everything runs in your browser. No accounts, no tracking,
  no decisions ever leave the device. Works offline.

## Features

| Section | What you can do |
| --- | --- |
| Simulate | Three decision-game scenarios: a Milgram-inspired lab deception study, an online mental-health survey, and a school-based study with 13-year-olds |
| Decisions | 15 decision points with feedback on informed consent, deception, protection from harm, right to withdraw, confidentiality & data protection, and debriefing |
| Verdicts | Committee decision (Approved / Minor revisions / Major revisions) with a per-principle scorecard and model answers |
| Principles | Plain-English cards on all six principles, plus "when is deception ever justified?" and "vulnerable participants & gatekeeper consent" |
| My report | Full decision record, principle tally, reflection prompts, HTML export, one-click erase |

Plus: automatic dark mode, keyboard-accessible tabs with deep links (`#principles`),
and no dependencies of any kind.

## Run it

Everything is a **single HTML file** — `index.html`. No build step, no
dependencies, nothing to install.

- **Locally:** just double-click the file, or
  `python3 -m http.server` in this folder and visit `http://localhost:8000/index.html`.

## Deploy to GitHub Pages

1. Create a new public repository (e.g. `ethics-simulator`).
2. Upload the folder contents (README, index.html, LICENSE) to the repository root.
3. Settings → Pages → Deploy from branch → `main` / `(root)`.
4. Your tool is live at `https://<username>.github.io/ethics-simulator/`.

## Licence & reuse

Free to use, share and adapt for teaching. Attribution appreciated. Scenarios are
fictional composites built for discussion — a teaching aid, not legal advice.
