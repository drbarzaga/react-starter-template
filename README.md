## Boilerplate - React + TypeScript + Babel + Webpack + EsLint + Prettier

Setting Up React, Babel, TypeScript, Webpack, Eslint, Prettier without `npx create-react-app` fallowing this [Guide](https://dev.to/rinconcamilo/setting-up-react-babel-webpack-without-create-react-app-2a1f)

### Install Dependencies

> Before install the dependencies check the node version on `.nvmrc`, we recomend use a node version manager as `nvm`.

```bash
$ npm install
```

### Run Development Server

To run the webpack development server you can use the following command:

```bash
$ npm run start
```

### Build for Production

To build the application for production you can use the following command:

> This command will generate the compiled version of the application ready to deploy.

```bash
$ npm run build
```

### Run Code Checks

To run the Code checks with Eslint execute the fallowing command:

> Run code checks

```bash
$ npm run lint
```

> Fix the problems found

```bash
$ npm run lint:fix
```

### Packages

- [react](https://www.npmjs.com/package/react) - Will only have the needed functionality in order to define your React components.
- [react-dom](https://www.npmjs.com/package/react-dom) - Serves as the entry point to the DOM and server renders for React.
- [@babel-core](https://babeljs.io/docs/babel-core) - Babel compiler core.
- [@babel-preset-env](https://babeljs.io/docs/babel-preset-env) - Babel preset for each environment.
- [@babel/preset-react](https://babeljs.io/docs/babel-preset-react) - Babel preset for all React plugins.
- [babel-loade](https://webpack.js.org/loaders/babel-loader/) - Allows transpiling JavaScript files using Babel and Webpack.
- [webpack](https://www.npmjs.com/package/webpack) - Module bundler with the main purpose to bundle JavaScript files for the browser.
- [webpack-cli](https://www.npmjs.com/package/webpack-cli) - Command Line Interface (to execute webpack terminal lines).
- [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server) - Utilize webpack with a development server to provide live reloading.
- [html-webpack-plugin](https://webpack.js.org/plugins/html-webpack-plugin/) - Simplifies creation of HTML files to serve your bundles.
- [file-loader](https://www.npmjs.com/package/file-loader) - Resolves import/require() on a file into a url and emits the file into the output directory.
- [css-loader](https://webpack.js.org/loaders/css-loader/) - Interprets import and url like import/require and will resolve them.
- [style-loader](https://www.npmjs.com/package/style-loader) - Inject CSS into the DOM.
- [typescript](https://www.npmjs.com/package/typescript) - Adds optional types to JavaScript.
- [@types/react](https://www.npmjs.com/package/@types/react) - Type definitions for react.
- [@types/react-dom](https://www.npmjs.com/package/@types/react-dom) - Type definitions for react-dom.
- [@babel/preset-typescript](https://babeljs.io/docs/babel-preset-typescript#with-a-configuration-file-recommended) - Allows Babel to understand typescript.
- [eslint](https://www.npmjs.com/package/eslint) - Is a tool to identify and report on code patterns.
- [eslint-plugin-react](https://www.npmjs.com/package/eslint-plugin-react) - React specific linting rules for ESLint .
- [eslint-plugin-react-hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks) - Enforces the Rules of Hooks, is a part of the Hooks API for React.
- [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier) - Turns off ESLint rules that would conflict with Prettier's formatting.
- [prettier](https://www.npmjs.com/package/prettier) - An opinionated code formatter. Used to enforce a consistent style.
- [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser) - ESLint parser which leverages TypeScript ESTree to allow for ESLint to lint TypeScript source code.
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin) - ESLint plugin which provides lint rules for TypeScript codebases.
- [pre-commit](https://www.npmjs.com/package/pre-commit) - Is a `pre-commit` hook installer for git. It will ensure that your npm test (or other specified scripts) passes before you can commit your changes. This all conveniently configured in your package.json.
