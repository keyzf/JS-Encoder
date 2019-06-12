# Compiler ol

**一个 HTML + CSS + JS 在线编译器**

本编译器从[JS Bin](https://jsbin.com/?html,output)和[CODEPEN](https://codepen.io/pen/)这两个优秀的编译器中获得灵感,采用 Vue 框架,element-ui 和[CodeMirror](https://codemirror.net/)工具制作。

**CodeMirror**是一个功能非常强大的代码编译器,支持多种语言,功能多样且有多个主题样式

调用**CodeMirror**的 API 涉及到 DOM 操作,所以可以安装[vue-codemirror](https://www.npmjs.com/package/vue-codemirror)包来代替 CodeMirror

`npm install vue-codemirror --save`

---

一共有五个窗口： `HTML`,`CSS`,`JavaScript`,`Console`和`Output`

`Console`显示控制台输出的信息

`Output`显示效果

![截图未命名.jpg](https://i.loli.net/2019/06/12/5d00ec3466abb47300.jpg)

本人不才,现在编译器功能还很少,而且有些功能还没完善,比如自定义缩进等,可能还有很多 bug 没发现,之后会继续修复并且添加更多功能