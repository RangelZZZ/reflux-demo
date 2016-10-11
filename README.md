# reflux-demo
###克隆该项目至本地
git clone https://github.com/RangelZZZ/reflux-demo
###执行第一个 Demo（Reflux+React 实现页面渲染hello world！）
* 执行 npm install
* 执行npm run webpack
* 运行index.html

###执行第二个 Demo（Reflux+React 实现页面显示用户输入的文本内容）
* 修改 webpack.config.js中的entry属性为entry: './js/reflux-text.js',
* 执行npm run webpack
* 运行index.html

###执行第二个 Demo（Reflux+React+Express 实现页面渲染hello world！）
* 修改 webpack.config.js中的entry属性为entry: './js/reflux-api.js',
* 执行npm run webpack
* 执行npm start
* 访问 localhost:3000
