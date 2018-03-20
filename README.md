# do-line-segments-cross

A Node.js package that calculates if two given line segments (passed as four points) cross each other.

`doLineSegmentsCross(p1, q1, p2, q2)` where each parameter should have `x` and `y` properties properly set.

p1 & q1 are the coordinates that define the first line, and p2 & q2 are the coordinates that define the second line.

## Usage

First, install the package using npm:

    npm install do-line-segments-cross --save

Then, require the package and use it like so:

    var doLineSegmentsCross = require('do-line-segments-cross');

    console.log({x: 1, y: 1}, {x: 6, y: 6}, {x: 6, y: 6}, {x: 1, y: 1});    // true
    console.log({x: 1, y: 1}, {x: 6, y: 6}, {x: 2, y: 1}, {x: 7, y: 6});    // false

## License

MIT
