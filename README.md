# jscs-config-dev <a href="https://github.com/jscs/jscs"><img src="https://rawgit.com/ctate/jscs/master/.autocode/icon.svg" alt="JSCS Logo" width="90" height="90" align="right"></a>

[![NPM Version][npm-img]][npm-url]
[![Build Status][cli-img]][cli-url]
[![Licensing][lic-image]][lic-url]

[jscs-config-dev] is a shareable configuration package for [jscs].

## Install

Add [jscs] and [jscs-config-dev] to your project:

```sh
npm install --save-dev jscs jscs-config-dev
```

Then, add this configuration to your `package.json`:

```json
{
  "jscsConfig": {
    "extends": "dev"
  }
}
```

[npm-url]: https://www.npmjs.com/package/jscs-config-dev
[npm-img]: https://img.shields.io/npm/v/jscs-config-dev.svg
[cli-url]: https://travis-ci.org/jonathantneal/jscs-config-dev
[cli-img]: https://img.shields.io/travis/jonathantneal/jscs-config-dev.svg
[lic-url]: LICENSE.md
[lic-image]: https://img.shields.io/npm/l/jscs-config-dev.svg
[log-url]: CHANGELOG.md
[log-image]: https://img.shields.io/badge/changelog-md-blue.svg
[git-url]: https://gitter.im/postcss/postcss
[git-image]: https://img.shields.io/badge/chat-gitter-blue.svg

[jscs]: https://github.com/jscs-dev/node-jscs
[jscs-config-dev]: https://github.com/jonathantneal/jscs-config-dev
