**enum.js** implements enumerations in javascript.

Example:

```js
const enumjs = require('enum.js')

const DIR = enumjs('DIRECTION', 'north:n east:e south:s west:w')
DIR.north == DIR.n
```
