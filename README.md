# CareLinx Base Referral Form

Static HTML/CSS implementation of the CareLinx Base Referral Form design. Open `index.html` in a browser; no build step or dependencies.

- `current-state.html` — recommended structure: field usage and visibility across live programs.
- `proposal.html` — proposed interactive form. All interactivity (program selection, eligibility check, document upload, AI voice-fill walkthrough, ADL calculator modal) is pure CSS driven by hidden inputs and `:has()`, so it needs a current browser.
- `css/base.css` — shared tokens and components (badges, cards, fields); each page adds its own stylesheet.
