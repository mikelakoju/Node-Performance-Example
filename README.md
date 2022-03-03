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
* `pm2 start server.js -l logs.txt -i max` : to save the logs to a specified file
* `pm2 show 0` : will show details about that specific cluster 0
* `pm2 list` : to show a list of all clusters curently running
* `pm2 stop 4`: to stop cluster 4
* `pm2 start 4`: to start cluster 4
* `pm2 monit`: Gives a fancy Dashboard