## Getting started

```
yarn install
yarn start
```

## Debugging service workers

You may have noticed that running `yarn start` doesn't register any service workers.

That's because offline capabilities are confusion during development since you would always see the cached version
instead of the latest on with your changes.

You can debug service workers locally by building the production bundle and serving it like this:

```
yarn run build
yarn run serve
```
