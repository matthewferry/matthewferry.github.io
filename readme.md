Personal site for matthew-ferry.com using [Metalsmith](http://www.metalsmith.io)
for static site generation.

### Install dependencies
```shell
$ npm install
```

### Build site
Build a static directory, starts a server and watch for development.
```shell
$ npm start
```

### Write some markdown
Add or modify markdown files in `src/` for pages you want to create. File names
and directors become the route output, e.g. `src/foo.md` will
become `/foo/index.html` and `src/foo/bar.md` will become `/foo/bar/index.html`.

### Deploy
When you're ready to deploy your changes, run the deploy script, `npm run deploy`.
