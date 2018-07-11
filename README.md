# webpack
基于webpack4.0

> Webpack 是一个前端资源加载/打包工具。它将根据模块的依赖关系进行静态分析，然后将这些模块按照指定的规则生成对应的静态资源。  

## 为什么需要打包？  
常规的开发方式` html`、`css`、`jquery`比较落后，将文件交给后端。
Webpack 可以将多种静态资源` js`、`css`、`less` 转换成一个静态文件，减少了页面的请求  
MVVM 开发时代， 一切皆可打包  

![webpack示意图](http://www.runoob.com/wp-content/uploads/2017/01/what-is-webpack.png)  

webpack 将现代`js`开发中的各种新型有用的技术，集合打包，打包前无法运行，(js es6 module,stylus等不支持浏览器直接执行，`.hbs` 模板编译， `.vue`) 在目标容器上运行  


