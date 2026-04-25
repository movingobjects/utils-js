# Utils (js)

An ES6 JavaScript utility library.

## Installation

```shell
npm install @movingobjects/utils-js --save
```

## Usage

Load entire library.

```js
import * as utils from '@movingobjects/utils-js';

let isGoat = utils.random.boolean(2/3);
```

Load individual pieces.

```js
import { Range } from '@movingobjects/utils-js';

let countRange = new Range(1, 10);
```

```js
import { getLatin } from '@movingobjects/utils-js/text';

console.log(getLatin(15, true));
```
