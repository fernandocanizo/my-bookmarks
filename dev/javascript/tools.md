# Javascript Tools

- [Can I Use](https://caniuse.com/)

  Given a language feature you can check which browser's version supports it.

- [Node Green](https://node.green/)

  List of language features and its support on different Nodejs versions.

- [Socket](https://socket.dev/)
  > Detect and block software supply chain attacks
  > Socket is not a traditional vulnerability scanner. Socket proactively detects and blocks 70+ signals of supply chain risk in open source code, for comprehensive protection.

  Tells you if a package contains vulnerabilities by analyzing it's whole dependency tree.

## Registries

- [npmjs](https://www.npmjs.com/)
- [npms](https://npms.io/)
- [jsr](https://jsr.io/)

### To help decide which package

Not registries, but may help decide for a package when the other quality variables are even.

- [npm trends](https://npmtrends.com/)

## Code Quality

- [MemLab](https://facebook.github.io/memlab/)
  Analyzes JavaScript heap and finds memory leaks in browser and node.js

  **Didn't try yet**

- [PubLint](https://publint.dev/)
  Is a package validator. Useful to test your packages or also dependencies you plan to use to see if they have good quality. Also good to discriminate which package is producing an ESM/CJS problem when you don't know exactly which one is the responsible, example: Remix vs Radix-ui.

- [Are The Types Wrong?](https://arethetypeswrong.github.io/)
  Another one in the same vein as PubLint, I feel it more informational and also points to good documentation about the problem and possible fixes.
