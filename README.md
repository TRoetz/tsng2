## TSNG2

Minimal Boilerplate with TypeScript + Angular 2 + Electron (optional)

Use it to bootstrap your project.

### Install

To install dependencies run with shell:

```sh
$ npm install
```

When dependencies will be installed use gulp to build:

```sh
$ npm run build
```

To start lite server to test use:

```sh
$ npm run try-web
```

### Electron

To start project as desktop (electron) app use:

```sh
$ npm run try-desktop
```

And to pack native release use:

```sh
$ npm run pack-desktop
```

### Building

This boilerplate uses gulp to build. Watch command is also available if you develop it continiously:

```sh
npm run gulp watch
```

Minification is turned off by default. Use `--minify` flag to activate it:

```sh
npm run gulp build --minify
```

