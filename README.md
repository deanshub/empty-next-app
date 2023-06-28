# empty next app
> This repo is an experiment to see bundles over all next versions.


Create next app
```bash
npx create-next-app
```

Add next.config.js
```js
const withInItStats = require('next-in-it-stats/cjs')({
  legacy: true,
  name: 'empty next app',
});

const nextConfig = {
  reactStrictMode: true,
};

module.exports = withInItStats(nextConfig);
```

Add dependency
```bash
npm i next-in-it-stats
yarn add next-in-it-stats
```