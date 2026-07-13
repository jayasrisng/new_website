# new_website

`new_website` is a React/Vite web application built with a broad shadcn/Radix-style component stack and routes for product, support, privacy, careers, admin, wiki, and related pages.

This repository needs a content and route audit before it should be treated as the canonical public website.

## Current app routes

```text
/           Home/index
/about      About
/product    Product
/support    Support
/privacy    Privacy
/careers    Careers
/admin      Admin
/untitled   Untitled
/wiki       Wiki
```

## Tech stack

- React 18
- TypeScript
- Vite
- React Router
- TanStack React Query
- Radix UI components
- Tailwind CSS
- shadcn-style UI primitives
- better-sqlite3 dependency present in package configuration

## Local development

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
```

Preview:

```bash
npm run preview
```

Lint:

```bash
npm run lint
```

## Cleanup checklist

- Confirm what product or site this repo represents.
- Remove unused generated routes such as `/untitled` if they are not intentional.
- Verify whether `/admin` should exist in a public build.
- Review dependency list and remove unused packages.
- Add deployment instructions.
- Add screenshots once the canonical UI is confirmed.
- Check for secrets, private data, or placeholder copy before public release.

## Privacy and security note

Do not publish admin tooling, private data, credentials, or internal-only routes without review.
