*This repository is a mirror of the [component](http://component.io) module [llinares/isometric-convert](http://github.com/llinares/isometric-convert). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/llinares-isometric-convert`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# isometric-convert

  Convert isometric to cartesian coordinates and back

## Installation

  Install with [component(1)](http://component.io):

    $ component install llinares/isometric-convert

## API

```js
var convert = require('isometric-convert');
```

### toIsometric(cartX, cartY)

```js
convert.toIsometric(1, 1); // x: 0, y: 1
```

### toCartesian(isoX, isoY)

```js
convert.toCartesian(1, 1); // x: 1.5, 0.5
```

## License

  MIT
