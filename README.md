This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

Next.js has File based routing
src/app/page.tsx is main page

## Routes Group

to create new routes like profile page, class page do like this in src/app folder->
`dispense/page.tsx` for `/dispense`

make for signin, signup, user

## Dynamic Routes[]

A folder or file in the form `[slug]` defines a **dynamic** parameter in the route (e.g., `/blog/[slug]` might match `/blog/hello-world` or `/blog/another-post`).

Inside your components, you can access this parameter via `params.slug`.

# Hydration

**What is Hydration in Next.js?**

Hydration is the process by which a client-side JavaScript framework (such as React) takes over an already rendered HTML page and makes it interactive. In a Next.js application, pages are often server-rendered (SSR) or statically generated (SSG). The server sends a fully formed HTML document to the browser, allowing users to see meaningful content quickly (which is great for SEO and performance). Once the page arrives in the browser, React’s JavaScript bundle “hydrates” that static HTML by attaching event listeners and other interactive behaviors so that the page becomes a fully functional React application.
hydration.tsx
