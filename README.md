## 一个代码洁癖患者的前端项目配置

一些用于前端项目的 dotfiles，主要是跟编码规范相关的。

涉及到的工具：

- [x] [EditorConfig](http://editorconfig.org/)
- [x] [ESLint](http://eslint.org/)
- [ ] [TSLint](http://palantir.github.io/tslint/)
- [x] [CSScomb](http://csscomb.com/)
- [ ] [CSSLint](https://github.com/CSSLint/csslint)
- [ ] [stylelint](https://github.com/stylelint/stylelint)
- [ ] [Lesslint](https://github.com/ecomfe/node-lesslint)
- [ ] [SCSS-Lint](https://github.com/brigade/scss-lint)
- [ ] [htmllint](http://htmllint.github.io/)
- [ ] [htmlcs](https://github.com/ecomfe/htmlcs)

注：本项目的 .gitignore 文件本身也是前述 dotfiles 的一部分，可用于任何其他前端项目。


### 关于 CSS Lint 工具

根据笔者的考察，目前 CSS Lint 工具中规则最丰富的应当是 stylelint，不过它的 CLI 功能尚在开发中，所以决定暂时等待。
在此期间可以先用 CSSLint。

## 关于 HTML Lint 工具

目前看来 htmllint 和 htmlcs 项目的规则丰富程度较为接近，留待进一步考察后确定用哪个。
