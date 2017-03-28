## Private NPM

How to use a Git Repo as a private NPM dependency.

1. publish your npm module to git. (use this repository as an example.)

2. add your dependency

```bash
npm install git+https://git@github.com/scottpreston/private-npm.git --save
```
3. Use your dependency in some code.

```javascript
var test = require('private-npm');
test.run();
```
