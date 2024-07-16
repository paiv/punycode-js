Punycode
==
Basic string encoder and decoder, without domain stuff.

[![standwithukraine](docs/StandWithUkraine.svg)](https://ukrainewar.carrd.co/)


Usage:

```js
const punycode = require("./punycode")
let s = "Доброго вечора"
let p = punycode.encode(s)
let q = punycode.decode(p)
assert(q === s)
```

- [RFC 3492: Punycode](https://www.rfc-editor.org/rfc/rfc3492.html)

