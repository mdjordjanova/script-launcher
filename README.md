[![npm version](https://badge.fury.io/js/script-launcher.svg)](https://www.npmjs.com/package/script-launcher)
[![downloads-image](https://img.shields.io/npm/dm/script-launcher.svg)](https://www.npmjs.com/package/script-launcher)

# ![Logo](docs/readme-logo.png) Script Launcher

### Tools
* [node](https://nodejs.org/en/) - JavaScript runtime
* [nvm](https://github.com/creationix/nvm) - node version manager
* [tsc](https://www.typescriptlang.org/) - TypeScript
* [launch](https://www.npmjs.com/package/script-launcher) - Script Launcher

### Basic setup
``` bash
git clone git@gitlab.quilzer.net:bas/script-launcher.git
cd script-launcher

npm install
npm start
```

### Build & Publish
```
npm start lint
npm start build
cd dist
npm login
npm whoami
npm publish
```

### Resources
* [NPM Developer Guide](https://docs.npmjs.com/misc/developers#before-publishing-make-sure-your-package-installs-and-works)

### Dependencies 
* [cross-spawn - A cross platform solution to node's spawn and spawnSync.](https://www.npmjs.com/package/cross-spawn)
* [Inquirer.js - A collection of common interactive command line user interfaces.](https://www.npmjs.com/package/inquirer)
* [string-argv - Parses a string into an argument array to mimic process.argv.](https://www.npmjs.com/package/string-argv)
* [deepmerge - Merges the enumerable attributes of two or more objects deeply.](https://www.npmjs.com/package/deepmerge)
