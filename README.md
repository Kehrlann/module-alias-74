# Alternative to `module-alias` using TypeScript

Some users want to have to use [module-alias](https://github.com/ilearnio/module-alias) along with TypeScript, which usually doesn't work very well.
Additionally, TypeScript already has native support for aliasing paths. Here is a fully working example.

## How to:

To run in development mode, try:

```
  $ npm run dev
```

To compile and run as you would in prod mode:

```
  $ npm run prod
```

Which is basically equivalent to:

```
  $ node -r ./prod-paths.js ./dist/index.js
```
