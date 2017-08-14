# cz-conventional-changelog

Status:
[![npm version](https://img.shields.io/npm/v/cz-conventional-changelog.svg?style=flat-square)](https://www.npmjs.org/package/cz-conventional-changelog)
[![npm downloads](https://img.shields.io/npm/dm/cz-conventional-changelog.svg?style=flat-square)](http://npm-stat.com/charts.html?package=cz-conventional-changelog&from=2015-08-01)
[![Build Status](https://img.shields.io/travis/commitizen/cz-conventional-changelog.svg?style=flat-square)](https://travis-ci.org/commitizen/cz-conventional-changelog)

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/stevemao/conventional-changelog-angular/blob/master/index.js) standard.

#### Installing the command line tool
Installation is as simple as running the following command (if you see permission errors, reading [fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions) may help):

Install `commitizen` globally, if you have not already.

```
npm install -g commitizen
```

#### Conventional commit messages as a global utility

```
npm install -g magento-conventional-changelog
```

Create a `.czrc` file in your `home` directory, with `path` referring to the preferred, globally installed, `commitizen` adapter

```
echo '{ "path": "magento-conventional-changelog" }' > ~/.czrc
```

You are all set! Now `cd`into any `git` repository and use `git cz` instead of `git commit` and you will find the `commitizen` prompt.

Protip:  You can use all the `git commit` `options` with `git cz`, for example: `git cz -a`.

