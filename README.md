# Rollup Simple Project

A boilerplate for simple project using [rollup.js](https://rollupjs.org/), preconfigured with:

- [eslint](https://eslint.org/)
- [stylelint](https://stylelint.io/)
- [prettier](https://prettier.io/)
- [lint-staged](https://github.com/okonet/lint-staged)
- [husky](https://github.com/typicode/husky)
- SASS support using [postcss](https://github.com/egoist/rollup-plugin-postcss)


## Useful Scripts

**Build**

```
$ yarn build
```

Build production ready asset bundle into `dist` directory.


**Development Mode**

```
$ yarn dev
```

Build asset bundle then spin up a local web server in port `10009` and keep watching for file changes.


**Lint & Format**

```
$ yarn lint:format
```

Run linters and prettier for the whole project.
