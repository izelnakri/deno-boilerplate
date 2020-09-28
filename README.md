```
# Bundle the TS for frontend with deno:
$ deno bundle --importmap=import_map.json --unstable src/index.ts > dist/bundle.js

# Minify bundle with terser
$ terser dist/bundle.js -o dist/bundle-min.js

# run the html server
$ http-server .
```

[Demo website](http://console-demo.surge.sh/)
