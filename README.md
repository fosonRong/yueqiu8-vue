
## 安装

```bash
$ npm i -g smart-npm # 安装 snpm
$ snpm i
```

## 调试

## 线上展示
https://lmzz.weidiana.com/?code=021LvD8h29TlUG0G5f8h2oHD8h2LvD8X&state=1
目前这套商城是由我之前在的团队运营，需要完整代码和技术支持可以联系我向他们购买，这里只交流前端技术

```bash
$ npm run dev
```
## 介绍

```bash
1这是一个基于微信端的单页应用，使用到的技术栈有vue（js框架），vux(ui框架)，vue-router(路由)，VueResource(http插件),适合初学者学习
2 运行之后很多数据显示不出来对不对，当然了，因为你没有接口，这里不提供java的接口，因为那不是我做的，我也不会，抱歉了数据这块接口自己搞定，这里只提供代码演示。如果实在需要接口，可以加我扣扣私聊。
3 微信里面坑很多这里有个网页授权的txt文件，通过webpack打包后会放到根目录的
4 最近比较忙，等过段时间闲下来了，我会维护这个项目，把接口数据换成本地数据

```
## 目录架构
build	项目构建(webpack)相关代码
config	配置目录，包括端口号等。我们初学可以使用默认的。
node_modules	npm 加载的项目依赖模块
src	
包含了几个目录及文件：
assets: 放置一些图片，如logo等。
components: 目录里面放了一个组件文件，可以不用。
App.vue: 项目入口文件，我们也可以直接将组件写这里，而不使用 components 目录。
main.js: 项目的核心文件。
static	静态资源目录，如图片、字体等。
test	初始测试目录，可删除
.xxxx文件	这些是一些配置文件，包括语法配置，git配置等。
index.html	首页入口文件，你可以添加一些 meta 信息或统计代码啥的。
package.json	项目配置文件。
README.md	项目的说明文档，markdown 格式

## 公众号测试：
启动内网穿透工具：小米球Ngrok启动工具.bat
前缀名：wx
端口：9999