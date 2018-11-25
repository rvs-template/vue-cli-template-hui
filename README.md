# vue-cli-template-hui

> vue-cli template for hui;

Usage

```javascript
$ npm install -g vue-cli
$ vue init rvs-template/vue-cli-template-hui my-project
$ cd my-project
$ npm install
$ npm run dev
```

If port 8080 is already in use on your machine you must change the port number in /config/index.js. Otherwise npm run dev will fail.

## What's Included

- npm run dev: first-in-class development experience.

Webpack + vue-loader for single file Vue components.
State preserving hot-reload
State preserving compilation error overlay
Lint-on-save with ESLint
Source maps

- npm run build: Production ready build.

  - JavaScript minified with UglifyJS.
  - HTML minified with html-minifier.
  - CSS across all components extracted into a single file and minified with cssnano.
  - All static assets compiled with version hashes for efficient long-term caching, and a production index.html is - auto-generated with proper URLs to these generated assets.
  - Use npm run build --reportto build with bundle size analytics.

- npm run unit: Unit tests run in PhantomJS with Karma + Mocha + karma-webpack.

  - Supports ES2015+ in test files.
  - Supports all webpack loaders.
  - Easy mock injection.

- npm run e2e: End-to-end tests with Nightwatch.

  - Run tests in multiple browsers in parallel.
  - Works with one command out of the box:
  - Selenium and chromedriver dependencies automatically handled.
  - Automatically spawns the Selenium server.
