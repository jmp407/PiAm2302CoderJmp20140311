PiAm2302CoderJmp20140311
========================

Just my starts, skips, screw-ups, notes etc.  
Subject to deletion, abandonment and start over without a moments notice.  
Start by creating a readme a then syncing to my /home/pi/simpletest directory.

Maybe I'm using node wrong.

A simple web server/pi sensor reader in SimpleTest
Using node vs 0.10.??

Another simple web server in SimpleTest2
Try this from ref:  http://www.nodebeginner.org/  and then find the first instance of exports

Done: Create two new js files: index.js, server.js

index.js index has a 
    require for server.js
		sets a var called server.  Is this a process?
    Then requests the server function (start) in server.js

server.js
  server.js contains a require to http and
  functions in server.js contain all the server stuff
    the function start which contains the html request handler function.  And
    a function within the start function (onRequest) which handles the requests and
    sends a response "Hello World"
    
  The server is created by http.createserver etc
  Does express do this for me?
The following command should then start the server but may not work properly run as sudo.
sudo node index.js
	It does work when the correct js is run not the server.js
	I may want to call this something like main.
	coder uses index.js and app.js
		which is which?
  
