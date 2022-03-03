# Node-Performance-Example
Node Performance Example

### Author: Dr Mike Lakoju

#### `This is a Node.js example on performance. Leveraging Node clusters`

#### The application has been updated to use `PM2`
* To run:  `pm2 start server.js -i max`
* PM2 is handing the clusters
* "-i" in code above means instance
* NOTE that you can also specify the number of instances you want by > `pm2 start server.js -i 2` ( two instances)
* `pm2 start server.js -i max` will automatically allow you run the maximum that your machine can handle.
* `pm2 logs` : to see logs in realtime of whats happening on the server