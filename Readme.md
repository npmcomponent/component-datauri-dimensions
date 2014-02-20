*This repository is a mirror of the [component](http://component.io) module [component/datauri-dimensions](http://github.com/component/datauri-dimensions). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-datauri-dimensions`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# datauri-dimensions

  Parse the dimensions of a data URI png / jpeg

## Installation

    $ component install component/datauri-dimensions

## Example

```js
var size = require('datauri-dimensions');

var canvas = document.createElement('canvas');
canvas.width = 100;
canvas.height = 150;

var uri = canvas.toDataURL('image/jpeg');
console.log(size(uri));

var uri = canvas.toDataURL('image/png');
console.log(size(uri));
```

## License

  MIT
