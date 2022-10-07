<p align="center">
  <a href="https://www.clerk.dev/?utm_source=github&utm_medium=starter_repos&utm_campaign=capacitor_starter" target="_blank" align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./docs/clerk-logo-dark.png">
      <img src="./docs/clerk-logo-light.png" height="64">
    </picture>
  </a>
  <br />
</p>

# Clerk Capacitor Starter

This example shows how to use [Clerk](https://www.clerk.dev/?utm_source=github&utm_medium=starter_repos&utm_campaign=capacitor_starter) with [Capacitor.js](https://capacitorjs.com/).

[![chat on Discord](https://img.shields.io/discord/856971667393609759.svg?logo=discord)](https://discord.com/invite/b5rXHjAg7A)
[![documentation](https://img.shields.io/badge/documentation-clerk-green.svg)](https://docs.clerk.dev)
[![twitter](https://img.shields.io/twitter/follow/ClerkDev?style=social)](https://twitter.com/intent/follow?screen_name=ClerkDev)

---

**Clerk is Hiring!**

Would you like to work on Open Source software and help maintain this repository? [Apply today!](https://apply.workable.com/clerk-dev/)

---

## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

To run the provided example, you can use [serve](https://www.npmjs.com/package/serve):

```bash
npx serve
```

### Setup

1. Add the allowed_origins to your instance via Clerk Backend API

```
curl -X PATCH https://api.clerk.dev/v1/instance \
-H "Authorization: Bearer backend_key_goes_here" \
-H "Content-type: application/json" \
-d '{"experimental_allowed_origins": ["capacitor://localhost:3000"]}'
```

2. Initiate the Clerk object as shown in our [Clerk-Capacitor starter repo](https://github.com/clerkinc/clerk-capacitor-starter/blob/main/www/index.html). **Note this repo is WIP**.
