# GraphQL Loader plugin for CRACO

Forked version of [craco-graphql-loader](https://www.npmjs.com/package/craco-graphql-loader) with updated dependencies. Plugin for [craco](https://www.npmjs.com/package/@craco/craco) which allows configuring the [graphql-tag/loader](https://github.com/apollographql/graphql-tag#webpack-loading-and-preprocessing) inside of [react-scripts](https://www.npmjs.com/package/react-scripts) applications.

## Usage

Install

```bash
npm i craco-graphql-loader

# or

yarn add craco-graphql-loader
```

Add this plugin to your `craco.config.js`:

```js
const cracoGraphqlLoader = require("craco-graphql-loader");

module.exports = {
  plugins: [{ plugin: cracoGraphqlLoader }],
};
```

Then import any query:

```jsx
import MyQuery from "./MyQuery.graphl";
```

For further usage instructions visit: https://github.com/apollographql/graphql-tag

---

Made with love at [Payt B.V.](https://www.paytsoftware.com/). [We're hiring](https://payt.homerun.co/mediorsenior-fullstack-ontwikkelaar)!
