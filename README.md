# heroku-pximg-proxy

Please refer to [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs?singlepage=true) for deployment.

## ENV

- `PROTOCOL` - Specify the protocol of example URLs on index page. It may be useful when you are using a HTTPS CDN.
- `JSONSTORAGE` - [JsonStorage](https://jsonstorage.net/) ID. It will be used to store analytics data. You can get one by running `npm run create:jsonstorage` on local.
