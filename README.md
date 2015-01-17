# Learn Browserify

![Browserify Header](http://i.imgur.com/G7Ffa6q.png)

Browserify lets you require('modules') in the browser by bundling up all of your dependencies.

## Read

+ Website: http://browserify.org
+ Handbook: https://github.com/substack/browserify-handbook


## Basic Example

```sh
atom main.js
```

```js
var unique = require('uniq');

var data = [1, 2, 2, 3, 4, 5, 5, 5, 6];

console.log(unique(data));
```

```sh
browserify main.js -o bundle.js
```

Now open open **index.html** in your browser and open the
**developer console**.
