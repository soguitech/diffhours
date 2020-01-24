# diffhours
Difference between two hours

This package is very simple, it determine the existing number of hours between two hours. it's waiting two parameters(string) : `startTime` and `endTime`

## Installation

```shell script
yarn add diffhours

ou

npm install diffhours --save
```

## How can i use it
very simple

```javascript
const diffhours = require('diffhours');

console.log(diffhours('10:40', '01:10')) // 14H30
```