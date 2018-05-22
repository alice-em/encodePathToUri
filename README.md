A simple NPM to convert local file locations into URI acceptable strings.

How to install
```
npm install --save encode-path-to-uri
```

Example on usage
```javascript
const encodePathToUri = require('encode-path-to-uri');

const encodedPath = encodePathToUri('/home/user/caffiend/How to brew coffee.pdf');
console.log(encodedpath); // /home/user/caffiend/How%20to%20brew%20coffee.pdf
```
