# zen-sleep

Dependency-free promise-based sleeping.

## Installation

```sh
npm i zen-sleep -S
```

## Usage

```js
const sleep = require('zen-sleep');

// Sleep for 1 second and do something then.
sleep(1000).then(...);

// or
await sleep(1000);
```

## License

MIT licensed.
