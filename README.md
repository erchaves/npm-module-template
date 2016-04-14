# NPM-Package Template

* [Babel](http://babeljs.io/): includes [ES2015](http://babeljs.io/docs/plugins/preset-es2015/) + [Stage 2](http://babeljs.io/docs/plugins/preset-stage-2/) presets
* [Flow](http://flowtype.org/): A static type checker, designed to quickly find errors in JavaScript applications. Now only supports Unix.
* [ESLint](http://eslint.org/): The pluggable linting utility for JavaScript and JSX. Default configuration is [eslint-config-airbnb/base](https://www.npmjs.com/package/eslint-config-airbnb#eslint-config-airbnbbase).
* [Mocha](http://mochajs.org/): A feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun.
* [Chai](http://chaijs.com/): A BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.

## Usage

### Requirements
* NPM
* Git Client

### Installation

```sh
git clone https://github.com/Beingbook/npm-module-template.git my-module
cd my-moudle
npm install
```

### Lint

```sh
npm run lint
```

### Test

```sh
npm test
```

### Build and Deployment

You should edit your modules identifier in `package.json` before you publish your module.

```sh
npm run build
npm version [major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
npm publish
```
