# 📦 webpack scss js base bundle

Webpack 5 bundle using Sass with a hot dev server and an optimized production build.

## Installation

Clone this repo and yarn install.

```bash
yarn install
```

## Usage

### Development server

```bash
yarn start
```

You can view the development server at `localhost:8080`.

### Production build

```bash
yarn build
```

> Note: You can view all changes in project by using http://localhost:3000/ address.

## Features

- [webpack](https://webpack.js.org/)
- [Sass](https://sass-lang.com/)
- [Sass resources-loader](https://github.com/shakacode/sass-resources-loader/)

## Dependencies

### webpack

- [`webpack`](https://github.com/webpack/webpack) - Module and asset bundler.
- [`webpack-cli`](https://github.com/webpack/webpack-cli) - Command line interface for webpack
- [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) - Development server for webpack
- [`html-loader`](https://webpack.js.org/loaders/html-loader/) - Exports HTML as string

### Sass

- [`sass`](https://github.com/sass/dart-sass/) - A pure JavaScript implementation of Sass

### Loaders

- [`sass-loader`](https://webpack.js.org/loaders/sass-loader/) - Load SCSS and compile to CSS
- [`css-loader`](https://webpack.js.org/loaders/css-loader/) - Resolve CSS imports
- [`style-loader`](https://webpack.js.org/loaders/style-loader/) - Inject CSS into the DOM
- [`sass-resources-loader`](https://github.com/shakacode/sass-resources-loader/) - Load your SASS resources into every required SASS module

### Plugins

- [`html-webpack-plugin`](https://github.com/jantimon/html-webpack-plugin) - Generate HTML files from template

## Author

- [Albert](https://www.taniarascia.com)

## License

This project is open source and available under the [MIT License](LICENSE).
