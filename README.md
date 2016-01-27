# Coding Style Matters

An opinionated coding style guide/configuration set for front-end projects.

## Lint tools

- [x] [EditorConfig](http://editorconfig.org/) & [ECLint](https://github.com/jedmao/eclint)
- [x] [ESLint](http://eslint.org/)
- [x] [TSLint](http://palantir.github.io/tslint/)
- [ ] [stylelint](https://github.com/stylelint/stylelint)
- [ ] [lesshint](https://github.com/lesshint/lesshint)
- [ ] [SCSS-Lint](https://github.com/brigade/scss-lint)
- [x] [CSScomb](http://csscomb.com/)
- [ ] [htmllint](http://htmllint.github.io/)
- [ ] [htmlcs](https://github.com/ecomfe/htmlcs)
- [x] [remark-lint](https://github.com/wooorm/remark-lint)
- [ ] [markdownlint](https://github.com/DavidAnson/markdownlint)

### Notes on configuration files

- [TSLint might support dot-prefixed configuration file in the future](https://github.com/palantir/tslint/issues/315#issuecomment-74350035)
- [TSLint might support rulesDirectory property, which means that we will be able to utilize custom rules such as `tslint-eslint-rules` and `tslint-microsoft-contrib`, etc.](https://github.com/palantir/tslint/pull/800)

## Other tools that do not need a configuration file

- [JSON Lint](https://github.com/zaach/jsonlint)

## Notes on git configuration

- The `.gitignore` file is a part of this project as well, thus applicable to any other front end projects.
- Git may have bugs with `core.autocrlf=true` for CJK text files, see [https://github.com/cssmagic/blog/issues/22](https://github.com/cssmagic/blog/issues/22). Need reproducing.
