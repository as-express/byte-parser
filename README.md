
Convert bytes into human-readable sizes like `1 KB`, `1 MB`, etc.

## Install

```bash
npm install bytes-parser
```

## Usage

```js
const humanBytes = require("bytes-parser");

humanBytes(0); // "0 B"
humanBytes(1024); // "1 KB"
humanBytes(1048576); // "1 MB"
humanBytes(1073741824); // "1 GB"
```
