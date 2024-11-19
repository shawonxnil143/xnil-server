## Example 
```code
const nayan = require('xnil-server');

nayan.alldown('url')
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('Error downloading:', error);
  });
```
