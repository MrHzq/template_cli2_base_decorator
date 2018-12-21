# Vue 项目模板--Vue Cli 2 + Base + Vue 装饰器

## 已有配置

1. `vuex`：Vue 的状态管理模式，具体请看`store文件`
1. `scss`：CSS 预处理器

## 未有配置

1. UI 框架

## 已有插件

1. 封装了`hzqRouter`路由自动生成函数。具体代码请看[hzq-router](https://github.com/MrHzq/hzq-router)
1. 封装了`$api`接口请求方法，可通过`this.$api.**()`调用。具体代码请看[hzq-axios](https://github.com/MrHzq/hzq-axios)
1. 封装了`$tool`工具方法，可通过`this.$tool.**()`调用。具体代码请看[hzq-tool](https://github.com/MrHzq/hzq-tool/blob/master/validator.js)
1. 封装了`$getItem,$setItem,$copy`三个常用方法，可通过`this.$getItem()`等调用。具体代码请看[hzq-tool](https://github.com/MrHzq/hzq-tool/blob/master/index.js)

## 使用方式

1. 先安装脚手架[hzq-cli](https://www.npmjs.com/package/hzq-cli)：`npm i -g hzq-cli`
1. `h -V`：查看版本号，确保安装成功
1. `h i`：根据提示，选择框架`cli2_base`即可
