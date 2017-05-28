# mapsme-ge0

Convert ge0 codes from [MAPS.ME](http://maps.me/) to decimal coordinates. Port from PHP to Javascript from https://github.com/mapsme/ge0_url_decoder.

## Installation

via NPM: https://www.npmjs.com/package/mapsme-ge0

    npm install mapsme-ge0

## Usage


    var mapsmeGe0 = require('mapsme-ge0');
    var coordinates = mapsmeGe0.decode('B4srhdHVVt');
    console.log(coordinates);

    // Output: [ '64.5234', '12.1234', 4.25 ]
