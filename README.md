
Convert bytes into human-readable sizes like `1 KB`, `1 MB`, etc.

## Install

```bash
npm install bytes-parser
```

## Usage

```js
const humanBytes = require("bytes-parser");

bytesParser(0); // "0 B"
bytesParser(1024); // "1 KB"
bytesParser(1048576); // "1 MB"
bytesParser(1073741824); // "1 GB"
```
