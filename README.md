# awesome-remix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [Remix 💿](https://remix.run) packages and resources.

## Contents

- [Packages](#Packages)
- [Stacks](#Stacks)
- [Templates](#Templates)
- [Example Apps](#Example-Apps)
- [Snippets](#Snippets)
- [Videos](#Videos)
- [Blog Posts](#Blog-Posts)

## Packages

- [remix-auth](https://github.com/sergiodxa/remix-auth) - Simple Authentication for Remix
- [remix-utils](https://github.com/sergiodxa/remix-utils) - A set of utility functions and types to use with Remix.run
- [remix-i18next](https://github.com/sergiodxa/remix-i18next) - The easiest way to translate your Remix apps
- [remix-seo](https://github.com/chaance/remix-seo) - A package for easily managing SEO meta and link tags in Remix.
- [remix-params-helper](https://github.com/kiliman/remix-params-helper) - Helpers that make it simple to use Zod with URLSearchParams, FormData, and Remix params object
- [remix-tailwind](https://github.com/itsMapleLeaf/remix-tailwind) - Use TailwindCSS with Remix without an extra build step
- [remix-validated-form](https://github.com/airjp73/remix-validated-form) - A ValidatedForm component and helpers for easy client and server side form validation.
- [remix-themes](https://github.com/abereghici/remix-themes) - An abstraction for themes in your Remix app.
- [remix-routes](https://github.com/yesmeck/remix-routes) - Typesafe routing for your Remix apps.
- [remix-middleware](https://github.com/neurosnap/remix-middleware) - An express-like middleware system for remix loaders and actions
- [remix-crash](https://github.com/xstevenyung/remix-crash) - Get better insight on why your Remix app crashed during development 💥
- [remix-pwa](https://github.com/ShafSpecs/remix-pwa) - A package to integrate PWA features into Remix
- [superjson-remix](https://github.com/donavon/superjson-remix) - A solution for Remix that allows you to send binary data from your loader to your React client app
- [remix-etag](https://github.com/donavon/remix-etag) - Makes adding an ETag header to a response easy
- [domain-functions](https://github.com/seasonedcc/domain-functions/) - Decouple your business logic from your Remix actions and loaders. With first-class type inference from end to end.
- [remix-image](https://github.com/Josh-McFarlin/remix-image) - A React component for responsive images in Remix.
- [remix-forms](https://github.com/seasonedcc/remix-forms) - Magically create forms + actions in Remix
- [@sentry/remix](https://github.com/getsentry/sentry-javascript/tree/master/packages/remix) - Error and performance monitoring of your Remix apps with [Sentry](https://sentry.io/)
- [remix-sitemap](https://github.com/fedeya/remix-sitemap) - Sitemap generator for Remix applications
- [remix-auth-webauthn](https://github.com/alexanderson1993/remix-auth-webauthn) - A Remix Auth strategy for signing in with Web Authentication passkeys.

## Stacks

- [blues-stack](https://github.com/remix-run/blues-stack) - The Blues Stack: Deployed to the edge (distributed) with a long-running Node.js server and PostgreSQL database. Intended for large and fast production-grade applications serving millions of users.
- [indie-stack](https://github.com/remix-run/indie-stack) - The Indie Stack: Deployed to a long-running Node.js server with a persistent SQLite database. This stack is great for websites with dynamic data that you control (blogs, marketing, content sites). It's also a perfect, low-complexity bootstrap for MVPs, prototypes, and proof-of-concepts that can later be updated to the Blues stack easily.
- [grunge-stack](https://github.com/remix-run/grunge-stack) - The Grunge Stack: Deployed to a serverless function running Node.js with DynamoDB for persistence. Intended for folks who want to deploy a production-grade application on AWS infrastructure serving millions of users.
- [speed-metal-stack](https://github.com/Girish21/speed-metal-stack) - The Remix Blog Stack for deploying to Fly with MDX, SQLite, testing, linting, formatting, etc.
- [remix-worker-template](https://github.com/edmundhung/remix-worker-template) - All-in-one Remix Cloudflare worker template with tailwindcss, cypress, eslint and prettier
- [remix-edgedb](https://github.com/edgedb/remix) - Remix ft. EdgeDB, Tailwind, Fly, and cookie-based authorization
- [kpop-stack](https://github.com/netlify-templates/kpop-stack) - Create a Remix app with Netlify, Tailwind, TypeScript and more!
- [supa-fly-stack](https://github.com/rphlmr/supa-fly-stack) - The Remix Stack for deploying to Fly with Supabase, authentication, testing, linting, formatting, etc.
- [rockspec-stack](https://github.com/ShafSpecs/rockspec-stack) - A fully configurable & customizable Remix PWA stack.
- [dnb-stack](https://github.com/robipop22/dnb-stack) - The Remix Stack for deploying to Vercel with testing, linting, formatting, structure and mock for 3rd party API integration.
- [azure-remix-stack](https://github.com/aaronpowell/azure-remix-stack) - A remix stack template for running a remix app on Azure
- [remix-chop-suey-stack](https://github.com/jkcorrea/remix-chop-suey-stack) - Remix+EdgeDB+Tailwind+Fly.io=🖤
- [Stripe Stack](https://github.com/dev-xo/stripe-stack) - A Stripe focused Remix Stack that integrates User Subscriptions, Authentication and Testing. Driven by Prisma ORM. Deploys to Fly.io
- [cool-stack](https://github.com/tdsoftpl/cool-stack) - Template repository integrating Remix & Directus into a full-stack monorepo.

## Templates

- [remix-azure-template](https://github.com/danielgary/remix-azure-template) - Remix app deployed to Azure Functions
- [remix-nested-layouts](https://github.com/brookslybrand/remix-nested-layouts)
- [remix-tailwind-starter](https://github.com/mcansh/remix-tailwind-starter)
- [remix-on-netlify](https://github.com/ascorbic/remix-on-netlify)
- [remix-css-modules](https://github.com/jacob-ebey/remix-css-modules)
- [remix-auth-layouts-example](https://github.com/jacob-ebey/remix-auth-layouts-example/tree/main/app/routes)
- [remix-starter-kit](https://github.com/one-aalam/remix-starter-kit) - Remix ft. Supabase(Auth, CRUD, Storage) with other essentials - TailwindCSS, DaisyUI, ESLint, etc.
- [remix-edge-kit](https://github.com/one-aalam/remix-edge-kit) - Remix ft. Prisma(Railway.app/Planetscale)/FaunaDB/Supabase and other essentials but designed for Cloudflare workers

## Example Apps

- [kentcdodds.com](https://github.com/kentcdodds/kentcdodds.com)
- [hova-labs-remix](https://github.com/HovaLabs/hova-labs-remix)
- [snkrs](https://github.com/mcansh/snkrs)
- [realworld-remix.run](https://github.com/BenoitAverty/realworld-remix.run)
- [camchenry-remix](https://github.com/camchenry/camchenry-remix)
- [sergiodxa/personal-site](https://github.com/sergiodxa/personal-site)
- [metronome.sh](https://metronome.sh)
- [sergiodxa/collected-remix](https://github.com/sergiodxa/collected-remix)
- [Interactive Remix Routing](https://github.com/dilums/interactive-remix-routing)
- [Remix Ink](https://github.com/one-aalam/remix-ink)
- [jotyy/remix-portfolio](https://github.com/jotyy/remix-portfolio)
- [Runnable](https://github.com/kineticio/runnable) - Low-code admin workflows, built on Remix

## Snippets

- [HOWTO: Debug your server-side Remix code using VSCode](https://gist.github.com/kiliman/a9d7c874af03369a1d105a92560d89e9)
- [sitemap.xml generator](https://gist.github.com/andrelandgraf/0112631dcdf6640e4bd44360d3e7a08e)

## Videos

- [Introducing Remix v1 💿](https://www.youtube.com/watch?v=wsJaUjd1rUo)
- [CDN Caching, Static Site Generation, and Server Side Rendering](https://www.youtube.com/watch?v=bfLFHp7Sbkg)
- [Document Titles in Remix](https://www.youtube.com/watch?v=nXjMorEABFQ)
- [Live with Kent: Building Authentication with Postgres, Prisma, and Remix](https://www.youtube.com/watch?v=XkZINZDDdms)
- [Progressive Enhancement with Remix](https://www.youtube.com/watch?v=VM4VMESF3tU)
- [How to Add Nested/Persistent Layouts in Remix](https://www.youtube.com/watch?v=2QlxdDGqJ2c)
- [Introduction to HTTP Caching](https://www.youtube.com/watch?v=3XkU_DXcgl0)
- [Deploy Remix to Netlify Serverless Functions in less than 3 minutes](https://www.youtube.com/watch?v=tCGEoheZFfQ)
- [Remix Utah Meetup 2021-12-02](https://www.youtube.com/watch?v=YD3U6jo9epY)
- [Remix Tutorial with Kent](https://www.youtube.com/watch?v=hsIWJpuxNj0)
- [Interview to Michael Jackson at devtools-fm](https://www.youtube.com/watch?v=xI-OggjrKLg)
- [Remix Tutorial | Trying out the newest React Framework!](https://www.youtube.com/watch?v=SmMqdF2v30s)
- [Remix Run Speedrun - Pokemon](https://www.youtube.com/watch?v=rgZkd-RAYfE)
- [Remix is a NEW JavaScript framework you MUST try](https://www.youtube.com/watch?v=r4B69HAOXnA)
- [Playlist: Build A Fullstack App with Remix, Prisma & MongoDB](https://www.youtube.com/playlist?list=PLn2e1F9Rfr6kPDIAbfkOxgDLf4N3bFiMn)
- [Playlist: Build A Pet Management System With Remix, Prisma, and Postgres](https://www.youtube.com/watch?v=wqyHGQlZcws&list=PLTnRtjQN5ieYu9SdwLvzKYFVtfqySY7FT)

## Blog Posts

- [React Server Components and Remix](https://remix.run/blog/react-server-components)
- [On Rails](https://marbiano.dev/into-remix/on-rails)
- [First impressions with Remix](https://blog.vararu.org/remix)
- [Loader vs Route Cache Headers in Remix](https://sergiodxa.com/articles/loader-vs-route-cache-headers-in-remix)
- [The useMatches hook in Remix](https://sergiodxa.com/articles/the-usematches-hook-in-remix)
- [Validating Remix forms with Constraints API](https://sergiodxa.com/articles/validating-remix-forms-with-constraints-api)
- [Test Remix loaders and actions](https://sergiodxa.com/articles/test-remix-loaders-and-actions)
- [Use Fathom with Remix](https://sergiodxa.com/articles/use-fathom-with-remix)
- [Use NProgress in a Remix app](https://sergiodxa.com/articles/use-nprogress-in-a-remix-app)
- [How Remix makes CSS clashes predictable](https://kentcdodds.com/blog/how-remix-makes-css-clashes-predictable)
- [Super Simple Start to Remix](https://kentcdodds.com/blog/super-simple-start-to-remix)
- [Use ETags in Remix](https://sergiodxa.com/articles/use-etags-in-remix)
- [Stable Forms in Remix](https://dev.to/zachtylr21/stable-forms-in-remix-226p)
- [Generating Social Images with Remix](https://camchenry.com/blog/generating-social-images-with-remix)
- [Building a Simple Search UI with Remix](https://dev.to/zachtylr21/building-a-simple-search-ui-with-remix-57da)
- [Sending data from layout to leaf routes in Remix](https://sergiodxa.com/articles/sending-data-from-layout-to-leaf-routes-in-remix)
- [Using Service Workers with Remix](https://sergiodxa.com/articles/using-service-workers-with-remix)
- [Localizing Remix apps with i18next](https://sergiodxa.com/articles/localizing-remix-apps-with-i18next)
- [Adding CSRF protection to Remix](https://sergiodxa.com/articles/adding-csrf-protection-to-remix)
- [Load only the data you need in Remix](https://sergiodxa.com/articles/load-only-the-data-you-need-in-remix)
- [Server-Side authentication with Auth0 in Remix](https://sergiodxa.com/articles/server-side-authentication-with-auth0-in-remix)
- [Using TailwindCSS with Remix](https://sergiodxa.com/articles/using-tailwindcss-with-remix)
- [Jest Matchers for Remix responses](https://sergiodxa.com/articles/jest-matchers-for-remix-responses)
- [Using Form Objects inside Remix actions](https://sergiodxa.com/articles/using-form-objects-inside-remix-actions)
- [Route protection in Remix with Policies](https://sergiodxa.com/articles/route-protection-in-remix-with-policies)
- [Redirect to the original URL inside a Remix action](https://sergiodxa.com/articles/redirect-to-the-original-url-inside-a-remix-action)
- [Why Remix is worth your attention](https://blog.plasmic.app/posts/why-remix-is-worth-your-attention/)
- [Remix for Next.js Developers](https://blog.plasmic.app/posts/remix-for-nextjs-developers/)
- [Series: Build A Fullstack App with Remix, Prisma & MongoDB](https://www.prisma.io/blog/fullstack-remix-prisma-mongodb-1-7D0BfTXBmB6r)
- [Learn how to install Remix with Flowbite and Tailwind CSS](https://flowbite.com/docs/getting-started/remix/)
