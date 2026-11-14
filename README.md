

## Setup

--> take a look, this is a little different than usual!

1. Install the Vite+ CLI (`vp`):
   - macOS / Linux: `curl -fsSL https://vite.plus | bash`
   - Windows (PowerShell): `irm https://vite.plus/ps1 | iex`
2. Install dependencies: `npm install`
3. Install Playwright browsers (for E2E tests): `npx playwright install`

## Commands

- `vp dev`: start the dev server
- `vp check`: format, lint, and type-check
- `vp test`: run unit tests (Vitest)
- `vpr build`: full build with type-check
- `vp build`: bundle only (skips type-check)

Requires Node 22.18+ or 24.12+ (see `engines` in `package.json`).  
npm is
pinned to 12.2.2 via `devEngines`.