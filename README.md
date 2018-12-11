# zen-sleep-js ![bundlephobia badge](https://img.shields.io/bundlephobia/minzip/zen-sleep-js.svg) ![downloads number](https://img.shields.io/npm/dt/zen-sleep-js.svg)

Dependency-free promise-based sleeping.

## Installation

```sh
npm i zen-sleep-js -S
```

## Usage

```js
const sleep = require('zen-sleep-js');

// Sleep for 1 second and do something then.
sleep(1000).then(...);

// or
await sleep(1000);
```

## License

MIT licensed.
