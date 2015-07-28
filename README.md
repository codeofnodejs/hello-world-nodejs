
### Issue 1: Hello world with NodeJS

#### Simple basic:
- Step 1: Create server.js flie with content bellow:
```javascript
var http = require("http");

http.createServer(function(request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.write("Hello World");
  response.end();
}).listen(8888);
```

- Step 2: 
```javascript
node server.js
```
- Step 3: Open in your browser:
```http://localhost:8888/```
