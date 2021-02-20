# luhn-validator

[Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm) for nodejs

# Installation

```bash
npm i ng-luhn-validator-x
```

## Usage
```typescript
const luhn = require('luhn-validator-x');

luhn.luhnValidate('1234567890123456'); // return false
luhn.luhnValidate('5233756540063299'); // return true
```