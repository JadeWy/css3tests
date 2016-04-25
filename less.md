# less

less是一门css预处理语言

跟他一样的有 Sass $  Less @
> less可以让我们像变成一样，编写css

## 使用less
 1.客户端使用
 	必须在服务器环境下运行
 	//1. 写的要生成 css 的less代码
	<link rel="stylesheet/less" type="text/css" href="styles.less">

	//2. less.js库作用就是 编译less为css代码
	<script src="less.js"></script>

	//less.js 只能放在最后面
 2.服务端使用
 把 less 生成为 css 文件
 1.node.js
   javascript 运行在浏览器、运行在客户端
   node.js是JavaScript的一个服务器端的运行环境
   nodejs语法基于ECMAscript
   php jsp asp 一样，可以作为后台语言

   npm 包管理工具

   npm install 模块名
 例如：
   npm install jquery

   npm install http-server 提供http服务的一个包
   npm安装包的方式有两种：本地、全局
 ### 本地安装
   npm install jquery
   本地安装 会在当前目录下创建/node_modules/
   文件夹 安装的内容会放到这个目录下面


 ### 全局安装
 	npm install http-server
 	win8 c:/用户/用户名/隐藏文件夹AppData/Roaming/npm

 ### 卸载
 	 卸载本地包 npm uninstall 模块名
 	 ** 进入要卸载包的那个目录

 ### 更新模块
     更新模块   npm update 模块名
        		npm update -g 模块名
 安装less
 压缩less插件 less-plugin-clean-css



阈值 768 1000 1200

栅格数12

列间距15

导入@import "名字";

