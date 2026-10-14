# Renomedy Landing Page

A standalone landing page for Renomedy, a family medicine-routine coordination product in development.

**Product status:** Renomedy is not yet available. Product screens are illustrative concepts, not proof that a feature is live.

## Open in Codex

1. Open [this GitHub repository](https://github.com/LearnerForever-cyber/Renomedy-landing-pg) in Codex (or clone it into your local workspace and open that folder).
2. Let Codex read `AGENTS.md` first. It contains the project scope, product-truth guardrails, design direction, and validation workflow.
3. Ask Codex for a review or a specific change. Example: “Review the landing page for build errors, broken asset references, accessibility issues, and mobile layout problems. Don't deploy or change the main Renomedy app.”
4. Review the diff before accepting changes. Keep the work in this repository; the product app lives in a separate repository.

## Local development

Requirements: Node.js 20+ recommended and npm.

```sh
git clone https://github.com/LearnerForever-cyber/Renomedy-landing-pg.git
cd Renomedy-landing-pg
npm install
npm run dev
```

Vite prints the local preview URL in the terminal.

## Validation commands

```sh
npm run build
npm run lint
npm test
```

The build uses the existing Lovable TanStack configuration in `vite.config.ts`. Avoid manually re-adding plugins that this config already includes.

## Project stack

- React + TypeScript
- TanStack Start / TanStack Router
- Vite
- Tailwind CSS v4

## Design direction

Editorial and human, with warm paper tones, deep ink, muted botanical green, a restrained clay accent, generous whitespace, and mobile-phone product mockups. Avoid generic AI/SaaS visual tropes, unsupported claims, invented testimonials, and claims of unimplemented medical or security functionality.

## Important boundaries

- This repository is only the landing page; do not edit the separate [Renomedy product app](https://github.com/Team-Lucrion/Renomedy) unless explicitly requested.
- No launch date or open waitlist has been confirmed.
- Renomedy is intended for routine coordination, not medical advice or treatment decisions.
