# createIfNotExist
Synchronous Node.JS function to simply create a file if it does not exist.


```shell
npm install create-if-not-exist --save
```

```javascript
var createIfNotExist = require("create-if-not-exist");

createIfNotExist('file.txt','blablablabla');
```

##API

createIfNotExist(filename, data)
- **filename** - The name of the file
- **data** - The data to be written to the file
