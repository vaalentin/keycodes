# @vaalentin/keycodes

Javascript keycodes as an enum.

## Installation

```
$ npm install --save @vaalentin/keycodes
```

## Usage

The whole enum can be imported at once:

```js
import * as Keys from '@vaalentin/keycodes';

document.addEventListener('keydown', e => {
  if(e.keyCode === Keys.A) {
    // a is pressed
  }
});
```

Or just specific keycodes:

```js
import { A, B, C } from '@vaalentin/keycodes';

document.addEventListener('keydown', e => {
  if(e.keyCode === A) {
    // a is pressed
  }
});
```

## License

MIT, see [LICENSE.md](https://github.com/vaalentin/keycodes/blob/master/LICENSE.md) for more details.

