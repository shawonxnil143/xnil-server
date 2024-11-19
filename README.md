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
