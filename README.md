# Saints

**Note: this is a work in progress, and in its early stages.**

An [npm](https://www.npmjs.com/package/saints) module containing data about Catholics the Church has canonized, beatified or declared venerable, i.e. real life superheroes.

## Install

`npm install --save saints` or put [saints.json](https://github.com/jesse-blake/saints/blob/master/saints.json) in your project some other way.

## Use

Requiring saints results in a JavaScript object with three properties: 'canonized', 'beatified', and 'venerable':

```js
'use strict';

var saints = require('saints');

console.log(saints.canonized);
```

Or use [saints.json](https://github.com/jesse-blake/saints/blob/master/saints.json) some other way.
