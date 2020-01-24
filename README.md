# diffhours
Difference between two hours

This plugin is very simple, it determined the number of hours between two hours. it's waiting two parameters(string) : `startTime` and `endTime`

## Installation

```shell script
yarn add diffhours

ou

npm install diffhours --save
```

## How can i use it
very simple

```javascript
import diffhours from 'diffhours';

console.log(diffhours('10:40', '01:10')) // 14H30
```