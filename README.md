
Convert bytes into human-readable sizes like `1 KB`, `1 MB`, etc.

## Install

```bash
npm install bytes-parser
```

## Usage

```js
const parser = require("bytes-parser");

parser(0); // "0 B"
parser(1024); // "1 KB"
parser(1048576); // "1 MB"
parser(1073741824); // "1 GB"
```
