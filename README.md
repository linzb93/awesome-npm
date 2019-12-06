# awesome-tools

## 目录

- [babel](#babel)
- [css](#css)
- [debug](#debug)
- [express](#express)
- [ftp](#ftp)
- [git](#git)
- [http](#http)
- [markdown](#markdown)
- [Node](#node)
- [npm](#npm)
- [Promise](#promise)
- [react](#react)
- [stream](#stream)
- [vue](#vue)
- [webpack](#webpack)
- [测试](#%E6%B5%8B%E8%AF%95)
- [打印](#%E6%89%93%E5%8D%B0)
- [工具](#%E5%B7%A5%E5%85%B7)
- [进程](#%E8%BF%9B%E7%A8%8B)
- [路径](#%E8%B7%AF%E5%BE%84)
- [浏览器](#%E6%B5%8F%E8%A7%88%E5%99%A8)
- [命令行](#%E5%91%BD%E4%BB%A4%E8%A1%8C)
- [模板](#%E6%A8%A1%E6%9D%BF)
- [爬虫](#%E7%88%AC%E8%99%AB)
- [日志](#%E6%97%A5%E5%BF%97)
- [时间](#%E6%97%B6%E9%97%B4)
- [数字](#%E6%95%B0%E5%AD%97)
- [图片](#%E5%9B%BE%E7%89%87)
- [图形界面](#%E5%9B%BE%E5%BD%A2%E7%95%8C%E9%9D%A2)
- [文件](#%E6%96%87%E4%BB%B6)
- [系统](#%E7%B3%BB%E7%BB%9F)
- [颜色](#%E9%A2%9C%E8%89%B2)
- [验证](#%E9%AA%8C%E8%AF%81)
- [中国](#%E4%B8%AD%E5%9B%BD)
- [字符串](#%E5%AD%97%E7%AC%A6%E4%B8%B2)

## babel

* [babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) - 编译decorator的

## css

- [node-sass](https://github.com/sass/node-sass) - 将sass编译成css
- [autoprefixer](https://github.com/postcss/autoprefixer) - 为css语句添加前缀

## debug

* [debug](https://github.com/visionmedia/debug) - 调试工具，在调试模式下可以只针对某些功能进行调试
* [depd](https://github.com/dougwilson/nodejs-depd) - 提醒用户正在调用废弃的接口
* [pretty-error](https://github.com/AriaMinaei/pretty-error) - 美化错误提示

## express

* [body-parser](https://github.com/expressjs/body-parser) - 解析body
* [multer](https://github.com/expressjs/multer) - 解析上传的文件

## ftp

* [sftp-sync-deploy](https://github.com/dobbydog/sftp-sync-deploy) - FTP文件上传工具

## git

* [download-git-repo](https://github.com/flipxfx/download-git-repo) - 从Github、Gitlab这些地方下载git仓库
* [husky](https://github.com/typicode/husky) - pre git commit 和 pre git push 的钩子

## http

- [axios](https://github.com/axios/axios) - 常用的http请求工具
- [mockjs](https://github.com/nuysoft/Mock) - 伪造数据，http请求
- [ua-parser-js](https://github.com/faisalman/ua-parser-js) - 解析User-Agent
- [detect-port](https://github.com/node-modules/detect-port) - 检测端口是否被占用，并推荐没有被占用的端口号
- [on-finished](https://github.com/jshttp/on-finished) - http服务器关闭时的回调函数
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - 创建与验证web token

## markdown

* [markdown-it](https://github.com/markdown-it/markdown-it)-  解析markdown的
* [doctoc](https://github.com/thlorenz/doctoc) - markdown目录生成工具

## Node

* [cross-env](https://github.com/kentcdodds/cross-env) - 设置Node环境变量
* [nodemon](https://github.com/remy/nodemon) - Node代码更新后，服务器自动重启
* [builtin-modules](https://github.com/sindresorhus/builtin-modules) - Node内置module

## npm

* [npm-try-cli](https://github.com/luin/npm-try) - 在命令行里就可以简单使用npm模块，无需在编辑器里编辑
* [npm-check](https://github.com/dylang/npm-check) - 检查可更新的、错误的(有引用却没在package.json里出现)、无用的(在package.json里出现却没有用到) npm包
* [semver](https://github.com/npm/node-semver) - 版本验证库
* [pkg-conf](https://github.com/sindresorhus/pkg-conf) - 获取项目package.json信息

## Promise

* [p-each-series](https://github.com/sindresorhus/p-each-series) - 所有异步代码可以在队列中按顺序执行
* [pify](https://github.com/sindresorhus/pify) - 函数Promise化
* [is-promise](https://github.com/then/is-promise) - 判断是否是Promise实例


## react

* [redux](https://github.com/reduxjs/redux) - react的状态管理工具
* [redux-saga](https://github.com/redux-saga/redux-saga) - redux的异步行为中间件
* [redux-logger](https://github.com/LogRocket/redux-logger) - redux查看state的中间件
* [react-router](https://github.com/ReactTraining/react-router) - react的路由管理
* [reselect](https://github.com/reduxjs/reselect) - 缓存redux state派生的数据，减少中间的计算量
* [classnames](https://github.com/JedWatson/classnames) - 用来控制类名的工具，代码可读性高
* [immer](https://github.com/immerjs/immer) - 生成不可变数据
* [ant-design](https://github.com/ant-design/ant-design) - react的UI库
* [ant-design-pro](https://github.com/ant-design/ant-design-pro) - react后台管理系统解决方案, UI选用ant design
* [umi](https://github.com/umijs/umi) - react脚手架
* [next](https://github.com/zeit/next.js) - react服务端渲染
* [prop-types](https://www.npmjs.com/package/prop-types) - react props验证
* [react-html-table-to-excel](https://github.com/zsusac/ReactHTMLTableToExcel) - 将react table导出为excel
* [react-image-crop](https://github.com/DominicTobias/react-image-crop) - 图片裁切
* [react-computed-props](https://github.com/pbeshai/react-computed-props) - 提供类似于vue的计算属性功能
* [braft-editor](https://github.com/margox/braft-editor) - react富文本编辑器

## socket

* [ws](https://github.com/websockets/ws) - Websocket，可用于客户端和服务端
* [socket.io](https://github.com/socketio/socket.io) - Node实时通讯框架

## stream

* [through2](https://github.com/rvagg/through2) - 直观的处理流数据，不需要在on('data')里面处理
* [pump](https://github.com/mafintosh/pump) - 结合读写stream，在其中一个stream被销毁时自动销毁其他stream，无需手动处理
* [into-stream](https://github.com/sindresorhus/into-stream) - 将string或buffer类型的转成stream
* [get-stream](https://github.com/sindresorhus/get-stream) - 将stream转换成string或buffer类型的

## url

* [normalize-url](https://github.com/sindresorhus/normalize-url) - url规范化

## vue

* [vuex](https://github.com/vuejs/vuex) - vue的状态管理工具
* [vue-router](https://github.com/vuejs/vue-router) - vue的路由管理
* [element](https://github.com/ElemeFE/element) - vue的UI库

## webpack

- [webpack-merge](https://github.com/survivejs/webpack-merge) - 用来合并webpack的配置项
- [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) - webpack搭建开发环境的中间件
- [webpack-hot-middleware](https://github.com/webpack-contrib/webpack-hot-middleware) - webpack热更新的中间件
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - webpack分析依赖包的大小

## 测试

- [mocha](https://github.com/mochajs/mocha) - 测试框架
- [chai](https://github.com/chaijs/chai) - 断言库，支持多种风格的断言(例如assert、should、expect)

## 打印

* [chalk](https://github.com/chalk/chalk) - 命令行着色美化库
* [boxen](https://github.com/sindresorhus/boxen) - 在命令行里用边框包裹输出内容
* [figures](https://github.com/sindresorhus/figures) - 在命令行里输入图标
* [progress](https://github.com/visionmedia/node-progress) - 在命令行显示进度条
* [ora](https://github.com/sindresorhus/ora) - 可以在命令行里输出spinner
* [cliui](https://github.com/yargs/cliui) - 用类似css的方式控制命令行显示
* [cli-cursor](https://github.com/sindresorhus/cli-cursor) - 控制命令行光标显示隐藏，搭配progress这类命令行界面更新时光标不会隐藏的库
* [signale](https://github.com/klaussinani/signale) -  一个 Node 的命令行输出，自带 16 个级别，可以定制颜色和 Emoji
* [log-update](https://github.com/sindresorhus/log-update) - 在命令行输出帧动画
* [word-wrap](https://github.com/substack/node-wordwrap) - 输出内容分行显示
* [terminal-link](https://github.com/sindresorhus/terminal-link) - 在命令行输出链接
* [cli-columns](https://github.com/shannonmoeller/cli-columns) - 输出内容等宽纵向按顺序显示
* [cli-truncate](https://github.com/sindresorhus/cli-truncate) - 将部分输出内容转换为省略号
* [multispinner](https://github.com/codekirei/node-multispinner) - 同时生成多个spinner，适合并发的任务
* [gradient-string](https://github.com/bokub/gradient-string) - 渐变的字符串
* [term-size](https://github.com/sindresorhus/term-size) - 获取命令行的尺寸
* [wide-align](https://github.com/iarna/wide-align) - 内容居中显示

## 代码

* [prettier](https://github.com/prettier/prettier) - 代码格式化工具

## 工具

- [lodash](https://github.com/lodash/lodash) - 含有多个工具函数，包含数组，字符串，函数等类型
- [dot-prop](https://github.com/sindresorhus/dot-prop) 函数检索深对象属性没有时不会报错，只会返回undefined

## 进程

* [signal-exit](https://github.com/tapjs/signal-exit) - 进程结束的回调函数
* [execa](https://github.com/sindresorhus/execa) - child_process的升级版
## 路径

* [path-to-regexp](https://github.com/pillarjs/path-to-regexp) - 路径解析成正则表达式，例如'detail/:id'
* [minimatch](https://github.com/isaacs/minimatch) - 判断一个文件路径是否匹配glob方式的路径
* [relateurl](https://github.com/stevenvachon/relateurl) - 将路径最简化，包括简化成相对路径
* [slash](https://github.com/sindresorhus/slash) - 统一Windows和Linux平台的路径格式

## 浏览器

- [browser-sync](https://github.com/BrowserSync/browser-sync) - 浏览器热更新，文件监听等
- [open](https://github.com/sindresorhus/open) - 打开文件，网址等
- [store](https://github.com/marcuswestin/store.js) - 操作浏览器的localStorage
- [html2canvas](https://github.com/niklasvh/html2canvas) - HTML转换为canvas图片
- [webuploader](https://github.com/fex-team/webuploader) - 文件上传解决方案，兼容到IE6

## 命令行

- [shelljs](https://github.com/shelljs/shelljs) - 在js代码中运行shell语句
- [commander](https://github.com/tj/commander.js) - 管理命令行的参数
- [meow](https://github.com/sindresorhus/meow) - 便于创建命令行app
- [inquirer](https://github.com/SBoudrias/Inquirer.js) - 在命令行里发起问答

## 模板

- [shtml2html](https://github.com/librajt/shtml2html) - 编译shtml文件，转换成html
- [ejs](https://github.com/mde/ejs) - Node模板引擎

## 爬虫

* [puppeteer](https://github.com/GoogleChrome/puppeteer) - 功能最强大的爬虫工具，使用headless浏览器，支持模拟点击等功能抓取页面

- [cheerio](https://github.com/cheeriojs/cheerio) - 用jQuery api的方式读取html模板里的内容
- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 改变返回页面的encoding，如果页面charset是gbk的可以使用这个

## 日志

* [log4js](https://github.com/log4js-node/log4js-node) - Node标准日志库
* [bunyan](https://github.com/trentm/node-bunyan) - Node日志库，包含主机名称，进程号等信息


## 时间

* [ms](https://github.com/zeit/ms) - 把毫秒转化成标准时间格式
* [moment](https://github.com/moment/moment) - 功能丰富的日期库
* [timeago.js](https://github.com/hustcc/timeago.js) - 将时间格式化成"**时间之前"的

## 数字

* [chance](https://github.com/chancejs/chancejs) - 生成随机数据的库

## 图片

* [qrcode](https://github.com/soldair/node-qrcode) - 二维码生成工具
* [sharp](https://github.com/lovell/sharp) - node处理图片的库
* [imagemin](https://github.com/imagemin/imagemin) - 压缩图片的库，需要引入插件

## 图形界面

- [echarts](https://github.com/apache/incubator-echarts) - 可视化库
- [echarts-map-data](https://github.com/taozhiw/echarts-map-data) - 基于echarts的地图，包含世界各国，中国各省
- [area-data](https://github.com/linzb93/area-data) - 中国各省市县地区6位数编码

## 文件

- [del](https://github.com/sindresorhus/del) - 删除文件和文件夹
- [glob](https://github.com/isaacs/node-glob) - 文件查找，类似shell匹配文件的格式
- [glob-parent](https://github.com/es128/glob-parent) - 获取文件所在文件夹的路径
- [mkdirp](https://github.com/substack/node-mkdirp) - 提供递归的文件夹创建。在node V10.12.0后由fs.mkdir提供
- [bytes](https://github.com/visionmedia/bytes.js) - 把比特值转换成其他单位的
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - node的fs模块的拓展，支持Promise
- [rimraf](https://github.com/isaacs/rimraf) - 深层次的删除文件
- [treer](https://github.com/derycktse/treer) - 在命令行或者纯文本文件输出文件夹的文件树
- [chokidar](https://github.com/paulmillr/chokidar) - 监听文件变化的库
- [mime](https://github.com/broofa/node-mime) - 获取一个文件的mime type
- [find-up](https://github.com/sindresorhus/find-up) - 深度查找一个文件
- [file-type](https://github.com/sindresorhus/file-type) - 检测一个Buffer的文件类型

## 系统

* [node-notifier](https://github.com/mikaelbr/node-notifier) - 发出系统通知，兼容MacOs、Windows、Linux
* [address](https://github.com/node-modules/address) - 检测本机IP, mac等
* [clipboardy](https://github.com/sindresorhus/clipboardy) - 剪贴板
* [wallpaper](https://github.com/sindresorhus/wallpaper) - 设置/获取桌面壁纸
* [systeminformation](https://github.com/sebhildebrandt/systeminformation) - 获取系统详细参数

## 压缩

* [archiver](https://github.com/archiverjs/node-archiver) - 多文件压缩

## 颜色

* [color-convert](https://github.com/Qix-/color-convert) - 颜色格式转换
* [color-string](https://github.com/Qix-/color-string) - 颜色生成与解析
* [color](https://github.com/Qix-/color) - 颜色值转换与计算的库

## 验证

- [ajv](https://github.com/epoberezkin/ajv) - JSON Schema 验证
- [async-validator](https://github.com/yiminghe/async-validator) - 为表单提供验证，支持异步

## 移动端

* [dropload](https://github.com/ximan/dropload) - 移动端下拉刷新、上拉加载更多插件

## 中国

- [pinyin](https://github.com/hotoo/pinyin) - 汉字拼音转换工具
- [lunar-calendar](https://github.com/zzyss86/LunarCalendar) - 农历（阴历）万年历类库
- [Wavewindow](https://github.com/linzb93/Wavewindow) - 类似政府网站的飘窗

## 字符串

* [diff](https://github.com/kpdecker/jsdiff#readme) - 字符串比较
* [uuid](https://github.com/kelektiv/node-uuid) - 生成唯一的id
* [balanced-match](https://github.com/juliangruber/balanced-match) - 匹配括号对，包括"{}, (), <>"等
* [fill-range](https://github.com/jonschlinkert/fill-range) - 补齐一段距离中间的数字、字母