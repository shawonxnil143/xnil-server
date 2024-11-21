
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Doto&size=30&duration=4000&pause=1000&color=00FF00&background=000000&center=true&multiline=true&random=true&width=440&height=60&lines=Welcome+xnil-server)](https://git.io/typing-svg)


![npm](https://img.shields.io/npm/dw/xnil-server)
[![Npm Version](https://badge.fury.io/js/xnil-server.svg)](https://www.npmjs.com/package/xnil-server)
[![Month Downloads](https://img.shields.io/npm/dm/xnil-server.svg)](http://npm-stat.com/charts.html?package=xnil-server)
[![Npm Licence](https://img.shields.io/npm/l/xnil-server.svg)](https://www.npmjs.com/package/xnil-server)
## Example 
```code
const xnil = require('xnil-server');

xnil.alldown('url')
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('Error downloading:', error);
  });
```
