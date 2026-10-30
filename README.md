# myPortfolio — initial scaffold

This public repository currently contains the generated Next.js starter,
not a completed personal portfolio. The application at revision `9d5c996`
still renders the framework logo, editing instructions and documentation links.
Portfolio design work in the maintainer's original local checkout remains
uncommitted and is excluded from this presentation update.

For current project evidence, start with
[Ramtin's GitHub profile](https://github.com/boyInShadows).
A current deployed portfolio URL has not been verified. No portfolio screenshot
is presented because this public revision contains only the generated starter.

## Run the public scaffold

Verified with Node.js 24.11.1 and npm 11.6.2 on Windows. The lockfile pins
Next.js 15.5.2 and React 19.1.0; TypeScript and Tailwind CSS 4 are included.
Google font downloads need build-time network access. No application secrets,
backend or database are required.

```sh
git clone https://github.com/boyInShadows/myPortfolio.git
cd myPortfolio
npm ci
npm run dev
```

Open <http://localhost:3000>. Source starts at [app/page.tsx](app/page.tsx).

```sh
npx tsc --noEmit
npm run build
npm start
```

On 2026-10-30, a clean locked install, TypeScript check and production build
passed. Edge confirmed the starter renders without page errors. There is no
lint or test script and no hosted quality CI. These results verify the scaffold,
not a finished portfolio, deployment or production security. A dated dependency
audit reported six advisories (two critical, four high); no upgrades were made.
Existing framework attribution and rights remain unchanged.
