<h1 align="center">Welcome to nodets-boilerplate 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/timoxdev" target="_blank">
    <img alt="Twitter: timoxdev" src="https://img.shields.io/twitter/follow/timoxdev.svg?style=social" />
  </a>
</p>

> A basic boilerplate for any NodeJS + Typescript projects with a few packages to get started right away

## Install

```sh
git clone https://github.com/TimoZacherl/nodets-boilerplate.git
npm install
```

## Usage

*Typescript code should be written in the src folder and will be compiled into the dist folder. (Could be changed in the configs)*

```sh
npm run build
```
builds javascript code for production build into dist folder

```sh
npm run start
```
runs build script and starts the server

```sh
npm run start:dev
```
watches typescript source code and compiles on change whilst dev server is live

```sh
npm run lint
```
checks if code has any errors, which are described in the `.eslintrc` file with eslint

```sh
npm run lint-and-fix
```
runs eslint and fixes errors if possible

```sh
npm run prettier-format
```
formats code as described in `.prettierrc`

```sh
npm run prettier-watch
```
watches code and formats it on change

*Basic configurations for eslint, prettier, typescript and nodemon are contained in this repo.*

## Author

👤 **Timo Zacherl**

* Website: https://timozacherl.com
* Twitter: [@timoxdev](https://twitter.com/timoxdev)
* Github: [@timozacherl](https://github.com/timozacherl)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/TimoZacherl/nodets-boilerplate/issues). You can also take a look at the [contributing guide](https://github.com/TimoZacherl/nodets-boilerplate/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.buymeacoffee.com/timox" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" height="38">
</a>
<a href="https://www.patreon.com/timozacherl" target="_blank">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## 📝 License

Copyright © 2020 [Timo Zacherl](https://github.com/timozacherl).<br />
This project is [MIT](https://github.com/TimoZacherl/nodets-boilerplate/blob/master/LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_