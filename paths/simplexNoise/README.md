[![banner](https://particles.js.org/images/banner3.png)](https://particles.js.org)

# tsParticles Simplex Noise Path

[![jsDelivr](https://data.jsdelivr.com/v1/package/npm/tsparticles-path-simplex-noise/badge)](https://www.jsdelivr.com/package/npm/tsparticles-path-simplex-noise)
[![npmjs](https://badge.fury.io/js/tsparticles-path-simplex-noise.svg)](https://www.npmjs.com/package/tsparticles-path-simplex-noise)
[![npmjs](https://img.shields.io/npm/dt/tsparticles-path-simplex-noise)](https://www.npmjs.com/package/tsparticles-path-simplex-noise)

[tsParticles](https://github.com/matteobruni/tsparticles) path plugin for simplex noise movement.

## How to use it

### CDN / Vanilla JS / jQuery

The CDN/Vanilla version JS has one required file in vanilla configuration:

Including the `tsparticles.path.simplex.noise.min.js` file will export the function to load the path plugin:

```text
loadSimplexNoisePath
```

### Usage

Once the scripts are loaded you can set up `tsParticles` and the path plugin like this:

```javascript
loadSimplexNoisePath(tsParticles);

tsParticles.load("tsparticles", {
  /* options */
});
```

### ESM / CommonJS

This package is compatible also with ES or CommonJS modules, firstly this needs to be installed, like this:

```shell
$ npm install tsparticles-path-simplex-noise
```

or

```shell
$ yarn add tsparticles-path-simplex-noise
```

Then you need to import it in the app, like this:

```javascript
const { tsParticles } = require("tsparticles");
const { loadSimplexNoisePath } = require("tsparticles-path-simplex-noise");

loadSimplexNoisePath(tsParticles);
```

or

```javascript
import { tsParticles } from "tsparticles";
import { loadSimplexNoisePath } from "tsparticles-path-simplex-noise";

loadSimplexNoisePath(tsParticles);
```
