 <p align="center"><a href="https://webank.gitee.io/fes.js/" target="_blank" rel="noopener noreferrer"><img width="250" src="https://i.loli.net/2020/08/31/FB6zZyPEW5cVDAC.jpg" alt="Fes logo"></a></p>


# 前言
不管什么项目可能需要一个或者更多的管理台，管理台应用的内容一般是权限管理、增删改查、报表等业务逻辑相对固定的。但是大量的增删改查和接口联调非常耗费开发者时间，而且现在对管理台前端有了更高的要求，希望前端应用有美观而且统一的UI和一致的交互体验。     
Fes.js支撑从开发、联调、部署整个前端应用研发流程，提供模板项目、cli命令行工具、丰富的PC端组件和一系列API，提效中后台开发，让开发只关注如何用组件搭建出页面。


## 简介
Fes.js是一整套管理台前端应用解决方案，包含Fes-Cli、Fes-Core、Fes-UI三部分。
- Fes-Cli是命令行工具，一行命令创建工程、开启开发调试、打包发布。
- Fes-Core是运行时框架，固定页面布局，提供权限管理、储存管理、路由管理、接口管理、状态管理、数据字典管理、环境管理等API。以插件的方式提供扩展接口。
- Fes-UI是组件库，包含30+的PC端组件库，可以快速搭建出增删改查等页面

## Fes-Core 运行时架构
![fes-core.png](https://i.loli.net/2020/08/31/EGRcloxSnm41NeC.png)

## 页面举例

首页
![home.png](https://i.loli.net/2020/08/31/iDJ26GHcyZ9kpoh.png)

表单页面
![form.png](https://i.loli.net/2020/08/31/tjpM83vVo4KYN7x.png)

列表页面
![list.png](https://i.loli.net/2020/08/31/MHaOBf6xWXgzyRQ.png)
![listAndFrom.png](https://i.loli.net/2020/08/31/qXQgspFZkAmKW2H.png)
![listAndImg.png](https://i.loli.net/2020/08/31/ryQhUSTH5ZMdYVi.png)

## 使用

```bash
# install
npm install @webank/fes-cli -g

# create a project
fes init [project]

cd [project] && npm i

# start dev
npm run dev

# build
npm  run build
```

## 文档

详细使用请查看 [文档](https://webank.gitee.io/fes.js/)


## 社区联络微信群
![微信群](https://i.loli.net/2020/09/11/2XhKtPZd6NFVbDE.png)  

邮箱： harrywan@webank.com qlin@webank.com      
微信： geniusWc