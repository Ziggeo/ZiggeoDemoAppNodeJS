# Ziggeo Sample Application

This is a sample application to show you how to use our API using node.js. It has recording, uploading, update, delete, approve and reject function on it. While this application looks like cms it isn't one, because it doesn't contain authorization system whatsoever. If you want to improve it, feel free to add a pull request.

This application is using:

 * Node.js / [express](https://expressjs.com/)
 * [EJS template](https://ejs.co/)
 * [Ziggeo Node SDK](https://www.npmjs.com/package/ziggeo)

### Setting up variables

Add your `API_TOKEN` and `PRIVATE_KEY` that you get from ziggeo application to `.env-sample` file. Then rename `.env-sample` to `.env`. This will allow your application to use ziggeo API

## Getting Started

### Installing

This will install any library required from npmjs.org
```bash
$ npm install
```

Then make sure `temp_video/` folder is writeable by your code.

### Running

This command will run the our application.
```bash
$ node index.js
```
If there's no error showed you can check http://localhost:3000 in your browser.

## Contributing

Want to contribute or add changes? Feel free to do so. you can quickly do it by:
1. creating a fork of this repository
2. adding your own changes and pushing them to your fork
3. creating a pull request to add your code to ours

## License 

MIT Software License.

Copyright (c) 2017 Ziggeo
