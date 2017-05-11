[![Build Status](https://travis-ci.org/Moosecoop/PrettyLog.svg?branch=master)](https://travis-ci.org/Moosecoop/PrettyLog) [![node](https://rawgit.com/aleen42/badges/master/src/node.svg)](https://cdn.rawgit.com/aleen42/badges/master/src/node.svg) [![github](https://github.com/moosecoop/prettylog)](https://cdn.rawgit.com/aleen42/badges/master/src/github.svg) [![gitbook](https://moosecoop.gitbooks.io/prettylog/content/)](https://cdn.rawgit.com/aleen42/badges/master/src/gitbook_2.svg)
# PrettyLog
PrettyLog is a package to help make logging details to console more simple and look better.

## Usage
```javascript
var PrettyLog = require('prettylog');

console.log(prettyLog('Connected', false, false));
```

`prettyLog('Status set', false, false);` returns:

![result](https://i.imgur.com/Bf3LgNS.png "Logo Title Text 1")
