# gisvue说明

> 基于Vue+ElementUI+OpenLayers的前端架构

## 技术栈

> 技术栈 vue2 + vuex + vue-router + webpack + ES6/7 + elementUI + 阿里图标iconfont

## 目录结构
> ├── /build/ # 项目构建(webpack)相关配置<br>
  ├── /config/ # 项目开发环境配置<br>
  ├── /src/ # 源码目录<br>
  │ ├── /api/ # 请求接口<br>
  │ ├── /assets/ # 组件静态资源(图片)<br>
  │ ├── /components/ # 公共组件<br>
  │ ├── /router/ # 路由配置<br>
  │ ├── /vuex/ # vuex状态管理<br>
  │ ├── /views/ # 路由组件(页面维度)<br>
  │ ├── /config/ # 接口配置文件（请求地址）<br>
  │ ├── App.vue # 组件入口<br>
  │ └── main.js # 程序入口<br>
  ├── /static/ # 非组件静态资源<br>
  ├── .babelrc # ES6语法编译配置<br>
  ├── .editorconfig # 定义代码格式<br>
  ├── .eslintignore # ES6规范忽略文件<br>
  ├── .eslintrc.js # ES6语法规范配置<br>
  ├── .gitignore # git忽略文件<br>
  ├── index.html # 页面入口<br>
  ├── package.json # 项目依赖<br>
  └── README.md # 项目文档<br>

## 执行命令

```
# 安装依赖项
npm install

# 使用热重新加载 默认地址 localhost:8080
npm run dev

# 小型化生产建设
npm run build

# 为生产构建并查看bundle analyzer报告
npm run build --report
```
