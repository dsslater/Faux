# Faux

First you will need to create a file called `keys.config` it should take the form:

```
exports.keys = {
	client_id : 'YOUR CLIENT ID',
	client_secret : 'YOUR SECRET', 
	redirect_uri : 'http://localhost:8888/callback' 
}
```

run `npm install`
then run `node app.js`

App will be hosted on port 8888.
