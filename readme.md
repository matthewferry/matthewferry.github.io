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
Add or modify markdown files in `src/` for pages you want to create. Files and
directories are honored in the final route, e.g. `src/projects/index.md` will
become `/projects/index.html`.

### Publish
When ready to publish, stop the server, stage, commit, and push.
