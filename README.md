An example mailicious page used by an attacker for CSRF attack

## Running the server


1) Alternatively you can launch the app from the Terminal:

    $ node server.js

2) The default target of this app is OWASP Node Goat project Heroku instance
It can be pointed to another instance of node goat app by sending `target` query param in url with server name

Examples: 
https://nodegoat-csrf-attack.herokuapp.com
Sends POST request to https://nodegoat.herokuapp.com/profile by default

https://nodegoat-csrf-attack.herokuapp.com?target=http://localhost:3000
Sends POST request to http://localhost:3000/profile