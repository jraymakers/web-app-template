# Web App Template

Template for web apps built using:
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [TypeStyle](https://typestyle.github.io/)
- [Webpack](https://webpack.js.org/)

Also uses:
- [BasicServe](https://www.npmjs.com/package/basic-serve)
- [ESLint](https://eslint.org/)
- [FSExtra](https://www.npmjs.com/package/fs-extra)
- [JR](https://www.npmjs.com/package/jr)
- [Node](https://nodejs.org/)
- [NPM](https://www.npmjs.com/)

And supports:
- [VSCode](https://code.visualstudio.com/)

## Usage

Click the green "Use this template" button on the [main repository page](https://github.com/jraymakers/web-app-template).
(Or just follow [this link](https://github.com/jraymakers/web-app-template/generate).)

Choose a name for your new repository, create it, and create a local clone.

Run `npm install` to get dependencies.

This template uses the [JR](https://www.npmjs.com/package/jr) tool to run jobs.

Common jobs include:

- `jr build`

  Run development build. Compiles [TypeScript](https://www.typescriptlang.org/), lints with [ESLint](https://eslint.org/), bundles with [Webpack](https://webpack.js.org/). Output is written to the `out` directory.

- `jr buildProd`

  Same as `jr build`, but produces a minified, optimized output bundle suitable for deployment.

- `jr watch`

  Watches for changes and rebuilds as necessary. Uses `webpack --watch`.

- `jr serve`

  Runs a simple local web server for the static files in `out`. Uses [BasicServe](https://www.npmjs.com/package/basic-serve).

## Source

TypeScript source code for a skeleton web app is included.

The build depends directly the two files in `src/entry` (`index.html` and `main.tsx`) as well as `src/favicon/favicon.svg`.

A root React component (`Root`) is provided in `src/root/components`. Render your app here.

Some basic TypeScript and TypeStyle helpers are provided (in `src/typescript` and `src/style`). Use them or remove them, as desired.

## Maintenance

To update dependencies, [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) is recommended.

Install globally with `npm install -g npm-check-updates`.

Run `ncu` to list available updates.

Run `ncu -u` to update package.json to latest versions of all dependencies. More options are available for finer control.

Run `npm install` to install updates.
