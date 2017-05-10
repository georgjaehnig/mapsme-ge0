# mapsme-ge0

Convert ge0 codes from [MAPS.ME](http://maps.me/) to decimal coordinates. Port from PHP to Javascript from https://github.com/mapsme/ge0_url_decoder.

## Usage


    var mapsmeGe0 = require('mapsme-ge0');
    var coordinates = mapsmeGe0.decode('B4srhdHVVt');
    console.log(coordinates);

    // Output: [ '64.5234', '12.1234', 4.25 ]
