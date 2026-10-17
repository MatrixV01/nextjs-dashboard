## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Authentication

The login form submits `redirectTo` to Auth.js, using the requested `callbackUrl`
or `/dashboard` by default. This keeps the browser URL aligned with the rendered
dashboard so later Server Actions, including sign-out, reach the correct route.
Sign-out clears the session and redirects to `/`.

To check the flow, log in from `/login`, confirm the URL changes to `/dashboard`,
then sign out and confirm you return to `/`. Also check that visiting a protected
dashboard page while signed out returns you to that page after logging in.

## TypeScript in VS Code

This project uses TypeScript 7's native compiler and language service. Install
Microsoft's [TypeScript 7 extension](https://marketplace.visualstudio.com/items?itemName=TypeScriptTeam.native-preview)
(recommended by the workspace), then run **Developer: Reload Window**.
The workspace enables the native language service and points it to the local
`node_modules/typescript` package, not the legacy `lib/tsserver.js` path.

## Styling

This project uses Tailwind CSS v4 through the `@tailwindcss/postcss` plugin in
`postcss.config.js`. The global stylesheet imports Tailwind and explicitly loads
`tailwind.config.ts` to retain the custom theme and forms plugin.
