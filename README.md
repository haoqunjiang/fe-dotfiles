# Coding Style Matters

This repository contains a bunch of dotfiles, most of which are related to coding styles, for front-end and node.js projects.

## Lint tools

- [x] [EditorConfig](http://editorconfig.org/) & [ECLint](https://github.com/jedmao/eclint)
- [x] [ESLint](http://eslint.org/)
- [ ] [TSLint](http://palantir.github.io/tslint/)
- [ ] [stylelint](https://github.com/stylelint/stylelint)
- [ ] [Lesslint](https://github.com/ecomfe/node-lesslint)
- [ ] [SCSS-Lint](https://github.com/brigade/scss-lint)
- [x] [CSScomb](http://csscomb.com/)
- [ ] [htmllint](http://htmllint.github.io/)
- [ ] [htmlcs](https://github.com/ecomfe/htmlcs)
- [ ] [mdast-lint](https://github.com/wooorm/mdast-lint)
- [ ] [markdownlint](https://github.com/DavidAnson/markdownlint)

### Notes on configuration files

- [stylelint is working on a new configuration loader which is similar to eslint's](https://github.com/stylelint/stylelint/issues/490)
- [TSLint might support dot-prefixed configuration file in the future](https://github.com/palantir/tslint/issues/315#issuecomment-74350035)
- [markdownlint is considering to use key for rules instead of number](https://github.com/DavidAnson/markdownlint/issues/1)

## Other tools that do not need a configuration file

- [JSON Lint](https://github.com/zaach/jsonlint)

## Notes on git configuration

- The `.gitignore` file is a part of this project as well, thus applicable to any other front end projects.
- Git may have bugs with `core.autocrlf=true` for CJK text files, see [https://github.com/cssmagic/blog/issues/22](https://github.com/cssmagic/blog/issues/22). Need reproducing.
