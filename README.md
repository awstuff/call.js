# secure-call
Secure callback invocation. `secure-call` encapsulates callback validation and invocation into one simple function call. This means it checks whether the specified callback exists and is valid before calling it. 

## Installation
`npm install secure-call`

## Usage
The following code calls the callback `cb` with the arguments `true`, `212` and `"yay!"`, provided `cb` is a valid function:

```javascript
const call = require("secure-call");

call(cb, true, 212, "yay!");
```
