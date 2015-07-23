## Upcoming

- Fix runtime signature cache invalidation
- Provide error messaging for un-downloadable binaries
- Default to NODE_ENV=production for both build and runtime

## v77

- Skip npm bootstrapping with iojs

## v76

- Fix caching issues
- Use bin/release instead of generated Procfile
- Support OSX
- Simplify detect (package.json required)

## v74 / v75 (24/4/2015)

- Update build failure messaging and help

## v73 (24/4/2015)

- Disable cache restoration if node_modules already exists (eg from being git submoduled or checked into git)

## v72 (23/4/2015)

* Accept `cacheDirectories` array in package.json to override default `node_modules` caching