# @feathersjs/primus

[![Build Status](https://travis-ci.org/feathersjs/feathers.png?branch=master)](https://travis-ci.org/feathersjs/feathers)
[![Dependency Status](https://img.shields.io/david/feathersjs/feathers.svg?style=flat-square&path=packages/primus)](https://david-dm.org/feathersjs/feathers?path=packages/primus)
[![Download Status](https://img.shields.io/npm/dm/@feathersjs/primus.svg?style=flat-square)](https://www.npmjs.com/package/@feathersjs/primus)

> The Feathers Primus real-time API provider

## Installation

```
npm install @feathersjs/primus --save
```

## Quick example

```js
const feathers = require('@feathersjs/feathers');
const primus = require('@feathersjs/primus');

const app = feathers();

// Set up Primus with SockJS
app.configure(primus({ transformer: 'ws' }));

app.listen(3030);
```

## Documentation

Please refer to the [@feathersjs/primus documentation](https://docs.feathersjs.com/api/primus.html) for more details.

## License

Copyright (c) 2018

Licensed under the [MIT license](LICENSE).
