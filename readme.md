# 自定义包仓库

#### 文件说明：

- examples：存放本项目的示例用文件
- lib：存放编译结果（兼容浏览器，ES6 标准的 javascript 编译为 ES5）
- src：开发目录
- .babelrc：babel 的配置文件（使用 webpack 的话也可以写在 webpack.config 中）
- .gitignore：git 配置文件，配置忽略版本管理的对象
- .npmignore：npm 配置文件，配置发布到 npm 时的忽略对象
- index.js：统一导出的出口文件

- package.json：项目管理文件，项目初始化时自动生成
- readme.md：项目说明文件，可在新建仓库时生成该文件，根据项目内容自行编辑
