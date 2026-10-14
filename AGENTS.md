# Renomedy Landing Page — Codex Instructions

## Project scope
This repository is the standalone marketing landing page for Renomedy. Do not make changes to the separate product application repository (`Team-Lucrion/Renomedy`) unless explicitly asked.

## Product truth and copy
- Renomedy is in development and is not yet available.
- Treat screens and interactions as concepts unless code and product status verify otherwise.
- Do not claim that medical advice, medication-interaction checking, prescription scanning, secure storage, privacy certifications, or other unimplemented features exist.
- Be clear that Renomedy supports routine coordination, not medical decisions or medical advice.
- Do not invent a launch date, open waitlist, testimonials, adoption numbers, or clinical outcomes.

## Design direction
- Editorial, calm, human, and healthcare-appropriate — not generic AI/SaaS.
- Preserve the warm paper background, deep ink, muted botanical green, and restrained clay accent.
- Favor generous whitespace, strong typography, asymmetric composition, fine rules, and realistic mobile-phone UI mockups.
- Avoid gradients, glowing blobs, excessive rounded floating cards, generic icon tiles, and unsupported social proof.
- The desktop page should remain a desktop-width composition; the hero's product visuals are mobile-phone mockups.
- Keep responsive layouts and reduced-motion support.

## Engineering workflow
- Use TypeScript and the existing TanStack Start + React + Vite setup.
- Follow the existing path alias conventions (for example, `@/components/...`).
- Do not manually add Vite plugins already included by `@lovable.dev/vite-tanstack-config`; see `vite.config.ts`.
- Keep accessible labels, keyboard interaction, focus visibility, semantic headings, and responsive behavior.
- Prefer small, focused changes. Avoid unrelated dependency upgrades or broad rewrites.
- Never claim a command passed unless it was actually run and its result checked.

## Before finishing
1. Install dependencies with `npm ci` if a lockfile exists; otherwise use `npm install` and report that no lockfile was present.
2. Run `npm run build`.
3. Run `npm run lint` and `npm test -- --run` only if those scripts/configurations are supported; report any pre-existing failures clearly.
4. Summarize changed files, validation performed, and anything that still needs human review.
