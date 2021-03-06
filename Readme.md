
# china-province-city-district

  An util to query china province, city and district data.

## How to use

```javascript
var china = require('china-province-city-district');
// get all provinces
var provinces = china.query();
// get all citys for 陕西省
var citys = china.query('陕西省');
// get all districts for 咸阳市
var districts = china.query('咸阳市');
```

## See also
 
 - https://en.wikipedia.org/wiki/Provinces_of_China
 - http://www.ccb.com/cn/OtherResource/bankroll/html/code_help.html 
 - https://libraries.io/npm/provincecityinchina/1.0.5
 - https://github.com/substack/provinces
 - https://github.com/clemsos/d3-china-map
 - https://github.com/qianjiahao/cn-province-city

## License 

(The MIT License)

Copyright (c) 2014 perfectworks &lt;perfectworks@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
