# Regression in esbuild

```sh
npm ci

node index.js
# will output 

npm run bundle
# executes esbuild index.js --bundle --outfile=out.js --format=esm

node out.js
# fail
```

