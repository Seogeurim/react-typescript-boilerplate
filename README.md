# 🌐 React X TypeScript Boilerplate

React X TypeScript boilerplate using Babel, Sass with a hot dev server and a production build.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

## Getting Started

### Installation

```bash
git clone https://github.com/Seogeurim/react-typescript-boilerplate.git
cd react-typescript-boilerplate
yarn install
```

### Development server

Webpack dev server runs at `localhost:8000`.

```bash
yarn start
```

### Production build

Build outputs are created in `dist`.

```bash
yarn run build
```

## Features

- [webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [Sass](https://sass-lang.com/)

## Dependencies

### webpack

- [`webpack`](https://github.com/webpack/webpack) - Module and asset bundler.
- [`webpack-cli`](https://github.com/webpack/webpack-cli) - Command line interface for webpack
- [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) - Development server for webpack
- [`webpack-merge`](https://github.com/survivejs/webpack-merge) - Simplify development/production configuration

### Babel

- [`@babel/core`](https://www.npmjs.com/package/@babel/core) - Transpile ES6+ to backwards compatible JavaScript
- [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env) - Smart preset for Babel

### Loaders

- [`babel-loader`](https://webpack.js.org/loaders/babel-loader/) - Transpile files with Babel and webpack
- [`sass-loader`](https://webpack.js.org/loaders/sass-loader/) - Load SCSS and compile to CSS
  - [`sass`](https://github.com/sass/dart-sass) - A pure JavaScript implementation of Sass
- [`css-loader`](https://webpack.js.org/loaders/css-loader/) - Resolve CSS imports
- [`style-loader`](https://webpack.js.org/loaders/style-loader/) - Inject CSS into the DOM

### Plugins

- [`html-webpack-plugin`](https://github.com/jantimon/html-webpack-plugin) - Generate HTML files from template
- [`mini-css-extract-plugin`](https://github.com/webpack-contrib/mini-css-extract-plugin) - Extracts CSS file per JS file which contains CSS

### Linters

- [`eslint`](https://github.com/eslint/eslint) - Enforce styleguide across application
- [`prettier`](https://github.com/prettier/prettier) - code formatter

## License

This project is licensed under the [MIT License](./LICENSE).
