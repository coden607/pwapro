# pwapro

**Status: SKELETON — no application code exists yet.**

## What this repo is

Intended project (per repo description): **AirBear PWA — Solar-Powered Rideshare & Mobile Bodega**.
Homepage is currently set to a Vercel deployment (`pwapro-seven.vercel.app`), which is outside this factory's deploy scope.

## What exists

- Agent-runtime policy files only: `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, `.github/copilot-instructions.md`
- All point to the canonical skills library: https://github.com/coden607/skills
- Single commit on `main`

## Promised vs missing

| Promised (description) | Status |
|---|---|
| PWA (installable, offline-capable) | ❌ no code, no `manifest.json`, no service worker |
| Rideshare + mobile bodega features | ❌ no UI, no logic, no data model |
| Any buildable artifact | ❌ no `package.json`, no source at all |

## Next steps to make this real

1. Scaffold the PWA (e.g. Vite/React or plain HTML+JS) with `manifest.json` + service worker, base-path aware for `/pwapro/`.
2. Build core screens: ride request, bodega catalog, solar-status widget.
3. Deploy static build to the `gh-pages` branch → served at `https://coden607.github.io/pwapro/`.
4. Do not rely on Vercel (blocked for this factory).

_Audited by factory wave2, 2026-10-08._
