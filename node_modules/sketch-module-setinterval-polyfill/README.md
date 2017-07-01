# sketch-module-setInterval-polyfill

A [setInterval](https://developer.mozilla.org/fr/docs/Web/API/WindowTimers/setInterval) polyfill for sketch.

## Installation

```bash
npm i -S sketch-module-setinterval-polyfill
```

## Usage

```js
import {setInterval, clearInterval} from 'sketch-module-setinterval-polyfill'

const interval = setInterval(
  (param) => console.log(param),
  1000,
  'hello world'
)

clearInterval(interval)
```
