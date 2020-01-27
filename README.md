# Browser String Hasher

A barebones function for getting a SHA256 hash of a string using the browser's native crypto module.

### Usage

```js
import sha from "browser-string-hasher"

sha("This other string")
  .then(hash => {
    console.log(hash)
  })

// "0d5a0597790745345842b61356016e3b24e83a7e6b0266618180c3a864bf25f1"
```
