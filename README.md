# zen-sleep-js

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
