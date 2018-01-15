# react-app-rewire-react-svg-loader

Forked from [react-app-rewire-svg-react-loader](https://github.com/codebandits/react-app-rewire-svg-react-loader), this rewire preset will add [react-svg-loader](https://github.com/boopathi/react-svg-loader) to a [`react-app-rewired`](https://github.com/timarney/react-app-rewired) config.

```javascript
/* config-overrides.js */

const rewireReactSvgLoader = require('react-app-rewire-react-svg-loader');

module.exports = function override(config, env) {
    // ...
    config = rewireReactSvgLoader(config, env);
    // ...
    return config;
}
```
