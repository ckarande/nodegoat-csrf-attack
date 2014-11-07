An example mailicious page used to create CSRF attack on NodeGoat App

## Running the server


1)  You can clone this app and run it locally. Launch the app from the Terminal:

    $ node server.js

2) The default target of this app is OWASP Node Goat project Heroku instance. However,
It can be pointed to another instance of node goat app by sending `target` query param in the url with server name

### Examples:

The page is hosted on heroku at -
`https://nodegoat-csrf-attack.herokuapp.com`
By default it sends POST request to https://nodegoat.herokuapp.com/profile

To change the target Nodegoat App instance to localhost, use URL:
`http://nodegoat-csrf-attack.herokuapp.com?target=http://localhost:3000`

This will send POST request to `http://localhost:3000/profile`