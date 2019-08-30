### JADE
---
https://github.com/dscape/jade

http://jade.tilab.com/

```js
var jade = require('jade');

var fn = jade.compile('string of jade', options);
var html = fn(locals);

var html = jade.render('string of jade', mare(options, locals));

var html = jade.renderFile('filename.jade', merge(options, locals));


```

```sh
npm install jade
jade --client --no-debug filename.jade
npm install jade -g
jade --help

```

```
```


