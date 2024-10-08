# Remix Tailwindcss Design System

## Setup

```bash
# install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

git clone git@github.com:luiscarlin/remix-tailwindcss-design-system.git
cd remix-tailwindcss-design-system

# use correct version of node
nvm install

# use pnpm
corepack enable pnpm

# install dependencies
pnpm install
```

## Development

Run the dev server

```bash
pnpm dev
```

## Deployment

First, build your app for production

```bash
pnpm build
```

Then run the app in production mode

```bash
pnpm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`


## References

- [Remix docs](https://remix.run/docs)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev)

