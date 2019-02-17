[![Build Status](https://travis-ci.org/mytee306/pluralize.svg?branch=master)](https://travis-ci.org/mytee306/pluralize)

[![Coverage Status](https://coveralls.io/repos/github/mytee306/pluralize/badge.svg?branch=master)](https://coveralls.io/github/mytee306/pluralize?branch=master)

# pluralize

A Node.js module that returns the plural form of any noun

## Installation

```sh
npm install pluralize --save
yarn add pluralize
bower install pluralize --save
```

## Usage

### Javascript

```javascript
var pluralize = require("pluralize")
var boys = pluralize.getPlural("Boy")
```

```sh
Output should be 'Boys'
```

### TypeScript

```typescript
import { getPlural } from "pluralize"
console.log(getPlural("Goose"))
```

```sh
Output should be 'Geese'
```

### AMD

```javascript
define(function(require, exports, module) {
  const pluralize = require("pluralize")
})
```

## Test

```sh
npm run test
```
