*This repository is a mirror of the [component](http://component.io) module [yyolk/random-border-style](http://github.com/yyolk/random-border-style). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yyolk-random-border-style`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# random-border-style

  Return a random CSS border-style

## Installation

    $ component install yyolk/random-border-style

## Usage

```js
var RandomBorderStyle = require("random-border-style");
function changeBodyBorder(){
  document.getElementById("body").style.border = "3px " + RandomBorderStyle() + " red";
}
changeBodyBorder();
```

## License

  MIT
