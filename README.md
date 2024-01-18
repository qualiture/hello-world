# hello-world

This simple 'hello world' package is intended to demonstrate why checking in a `package-lock.json` file is extremely important.

When used as a dependency in a calling NodeJS app, you could for insyance demonstrate:

 - What happens when the calling app _does not_ have a `package-lock.json` file.
 - What happens when the calling app _does_ have a `package-lock.json` file.
 - What versions actually end up in the `package-lock.json` file.
 - What is the difference in versions when using `npm i` and `npm ci`.
 - When you have a `package-lock.json` file, and the package to-be-installed is ouiyside the version range of the `package.json` file:
     - what will happen when you run `npm i`.
     - what will happen when you run `npm ci`.
 - etc