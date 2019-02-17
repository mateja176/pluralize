# mypluralize

A Node.js module that returns the plural form of any noun

## Installation

```sh
npm install mypluralize --save
yarn add mypluralize
bower install pluralize --save
```

## Usage

### Javascript

```javascript
var pluralize = require("mypluralize")
var boys = pluralize.getPlural("Boy")
```

```sh
Output should be 'Boys'
```

### TypeScript

```typescript
import { getPlural } from "mypluralize"
console.log(getPlural("Goose"))
```

```sh
Output should be 'Geese'
```

### AMD

```javascript
define(function(require, exports, module) {
  const pluralize = require("mypluralize")
})
```

## Test

```sh
npm run test
```
