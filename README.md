# nodets-boilerplate

> A basic boilerplate for any NodeJS + Typescript projects with a few packages to get started right away

I created this boilerplate for myself to get started with my Node + Typescript projects faster, without making the same basic things at the beginning every time. Maybe this repo will help other people too. 
If you have any improvements or whatsoever please open an Issue.

## Installation

```bash
$ git clone https://github.com/TimoZacherl/nodets-boilerplate.git
```
## Usage

Typescript code should be written in the `src` folder and will be compiled into the `dist` folder. (Could be changed in the configs)

The following scripts are provided:
```bash
$ npm run build
```
Builds javascript code for production build into `dist` folder

```bash
$ npm run start
```
Runs build script and starts the server

```bash
$ npm run start:dev
```
Watches typescript source code and compiles on change whilst dev server is live

```bash
$ npm run lint
```
Checks if code has any errors, which are described in the `.eslintrc` file with eslint

```bash
$ npm run lint-and-fix
```
Runs eslint and fixes errors if possible

```bash
$ npm run prettier-format
```
Formats code as described in `.prettierrc`

```bash
$ npm run prettier-watch
```
Watches code and formats it on change

Basic configurations for eslint, prettier, typescript and nodemon are contained in this repo.

## License

MIT © [Timo Zacherl](https://timozacherl.com)
