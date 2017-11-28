# nodejs_Doc
//
1. Downloads node.js 
	node-v8.9.1-linux-x64.tar.xz("https://nodejs.org/en/")

2. Verify Node.js Installation:
	$ nodejs -v
	$ npm -v
	$ which node
	$ which nodejs


file named:: webserver.js

var http = require('http');

http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/html'});
    res.end('Hello World!');
}).listen(8080);

3.  Now, start the web server using the below command. ("http://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/install-nodejs-ubuntu-debian-linux-mint-using-ppa.html")
	$ nodejs --debug webserver.js
	
4. hit the http://localhost:8080/

Display on browser Hello World


A. To install node package
