### Running

If you are using `pm2` to manage your node apps.

Use `pm2 start myconfig.config.json`. An example config is given in `local.config.json`
For production `pm2 start local.config.json`

### Setting up a custom url

Modify index.js to the url you would like to utilize. 
Make sure that src/views/env is setup with a proper base url. 