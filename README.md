# nextjs_hello_world — legacy Next.js admin template

This checkout is a **Next.js + TypeScript admin dashboard template** using `@paljs/ui`, styled components, and rich-text editor integrations. It derives from the original [PalJS Next.js admin template](https://github.com/paljs/nextjs-admin-template); the original README references that upstream repository.

## Verified package scripts

| Command | Meaning |
| --- | --- |
| `yarn dev` | Start Next.js development mode |
| `yarn build` | Build the web application |
| `yarn start` | Start the built server; `PORT` defaults to `3000` |
| `yarn export` | Run a build and request a static export through the historical `next export` interface |

The last command depends on the **actual pinned Next.js version** and may no longer work with newer releases. Only run it after resolving that compatibility explicitly. Files under `src/` and `public/` are the application assets; `package.json`, `tsconfig.json`, and `yarn.lock` define the build environment.

## Deployment and security

The template includes UI scaffolding, not proof of identity authorization, secure storage, or an operational admin backend. Review API routes, authentication and data handling before publishing any privileged administration UI. Never place secrets in browser-facing variables or commit real environment files.

**Status:** corrected from source/manifest inspection. No installation, build, tests, or deployment was performed.
