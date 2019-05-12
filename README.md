# Blog with 11ty and Sanity.io

Minimal blog with [Eleventy](https://11ty.io) and Sanity.

This is a monorepo with a pre-configured [Sanity Studio](https://www.sanity.io) (`/studio`) and a very basic setup of [Eleventy](https://11ty.io) (`/web`).

## Quick start

1. `npm install` in the project root folder on local
2. `npm run sanity-init` to reconfigure the studio with a new or existing project
3. `npm run dev` to start the Studio and 11ty in watch mode
    -  Sanity Studio runs on [localhost:3333](http://localhost:3333)
    - 11ty outputs the static files in `_site`
4. `npm run build` to build to production locally
