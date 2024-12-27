# @juunini/sleep

A simple sleep function for JavaScript.

## Installation

```bash
npm install @juunini/sleep
```

## Usage

### ES6

```javascript
import sleep from '@juunini/sleep';
// or // import { sleep } from '@juunini/sleep';

await sleep(1000); // Sleep for 1 second
```

### CommonJS

```javascript
const sleep = require('@juunini/sleep');

await sleep(1000); // Sleep for 1 second
```

### UMD in Browser

```html
<!-- Include the script in your HTML file -->
<script src="https://unpkg.com/@juunini/sleep"></script>

<script>
  (async () => {
    await sleep(1000); // Sleep for 1 second
  })();
</script>
```

## License

MIT
