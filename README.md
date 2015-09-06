# tilePuzzle

[![Code Climate](https://codeclimate.com/github/matthewfedak/tilePuzzle/badges/gpa.svg)](https://codeclimate.com/github/matthewfedak/tilePuzzle)
 
[![Build Status](https://travis-ci.org/matthewfedak/tilePuzzle.svg?branch=master)](https://travis-ci.org/matthewfedak/tilePuzzle)

*A simple sliding tile puzzle game jQuery plugin*

### Working Demo
Check out the [demo](http://matthewfedak.co.uk/tilePuzzle) here.

### Example Usage
HTML - Create a div element to bind the plugin to:
```html
<div id="puzzle"></div>
```
JS - Bind the plugin to your element and pass some config parameters
```javascript
$('#puzzle').tilePuzzle({
    'level': 4,
    'maxWidth': 300,
    'imageUrl': 'images/cristo-redentor-rio-de-janeiro-brazil.jpg'
});
```

### Plugin Options
- **level**: An integer *(3+)*
- **maxWidth**: width of puzzle *(px)*
- **imageUrl**: An image URL

## License

tilePuzzle is available under the [MIT license](http://opensource.org/licenses/MIT).
The photo of Christ the Redeemer in Rio De Janerio was taken by me August 2012.
