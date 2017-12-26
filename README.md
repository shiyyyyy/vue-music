# vue-music

> Vue2.0构建移动端音乐 App


## 效果截图
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music1.gif" width="250" height="450">  
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music2.gif" width="250" height="450"> 
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music3.gif" width="250" height="450">  
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music4.gif" width="250" height="450">  
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music5.gif" width="250" height="450">  
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music6.gif" width="250" height="450">
<img src="https://github.com/shiyyyyy/vue-music/blob/master/static/vue-music7.gif" width="250" height="450">

## 技术栈

【前端】

- `Vue`：用于构建用户界面的 MVVM 框架。它的核心是**响应的数据绑定**和**组系统件**
- `vue-router`：为单页面应用提供的路由系统，项目上线前使用了 `Lazy Loading Routes` 技术来实现异步加载优化性能
- `vuex`：Vue 集中状态管理，在多个组件共享某些状态时非常便捷
- `vue-lazyload`：第三方图片懒加载库，优化页面加载速度
- `better-scroll`：iscroll 的优化版，使移动端滑动体验更加流畅
- `Stylus`：css 预编译处理器
- `ES6`：ECMAScript 2015，使用了Promise、class等ES6的语法
- `axios`：vue官方推介的第三方组件，用于服务端通讯。
- `jsonp`：服务端通讯。抓取 QQ音乐数据


【自动化构建及其他工具】

- `webpack`：项目的编译打包
- `vue-cli`：Vue 脚手架工具，快速搭建项目
- `eslint`：代码风格检查工具，规范代码格式


## 注意

此音乐播放器数据全部来自 QQ 音乐，接口改变了就需要修改 `jsonp` 和 `axios` 代码

## 安装与运行

```
git clone https://github.com/shiyyyyy/vue-music.git

cd vue-music

npm install //安装依赖

npm run dev //服务端运行 访问 http://localhost:8080

npm run build  //项目打包 
```

### 欢迎star！

