## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

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
