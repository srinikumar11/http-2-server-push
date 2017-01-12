# HTTP Push example

This project was created to test HTTP2/Push. Its working well :-)
Notes
 1. Push works only on https
 2. Its a http2 feature
 3. Resources can be pushed from server for a page requested, 
    instead of requesting individual files from server.
 4. Useful for static assets can be pushed to client/browser

how to use<br />
 1. git clone 
 2. cd into project folder<br />
 3. npm install<br />
 4. generate ssl cert: `openssl genrsa -des3 -passout pass:x -out server.pass.key 2048`<br />
 5. node index.js<br />
 6. open https://localhost:8000/home<br />
 7. open developer console to check<br />