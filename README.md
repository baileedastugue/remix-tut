# R-r-r-remix

A completed version of the [Remix tutorial](https://remix.run/docs/en/main/start/tutorial) available on the [Remix site](https://remix.run/). At the moment, it's a straight-up, line-by-line recreation of their tutorial for learnin' purposes. I may or may not use this as a general playground for all things Remix going forward. We'll see!

- [Remix docs](https://remix.run/docs)

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `remix build`

- `build/server`
- `build/client`
