# gisvue说明

> 基于Vue+ElementUI+OpenLayers的前端架构

## 技术栈

> vue2 + vuex + vue-router + webpack + ES6/7 + elementUI + 阿里图标iconfont

## 目录结构

```bash
├── /build/          # 项目构建(webpack)相关配置
├── /config/         # 项目开发环境配置
├── /src/            # 源码目录
│ ├── /api/          # 请求接口
│ ├── /assets/       # 组件静态资源(图片)
│ ├── /components/   # 公共组件
│ ├── /config/       # 接口配置文件（请求地址）
│ ├── /router/       # 路由配置
│ ├── /views/        # 路由组件(页面维度)
│ ├── /vuex/         # vuex状态管理
│ ├── App.vue        # 组件入口
│ └── main.js        # 程序入口
├── /static/         # 非组件静态资源
├── .babelrc         # ES6语法编译配置
├── .editorconfig    # 定义代码格式
├── .eslintignore    # ES6规范忽略文件
├── .eslintrc.js     # ES6语法规范配置
├── .gitignore       # git忽略文件
├── .gisvue.iml      # idea配置文件忽略文件
├── index.html       # 页面入口
├── package.json     # 项目依赖
└── README.md        # 项目文档
```

## 执行命令

```bash
# 安装依赖项
npm install

# 使用热重新加载 默认地址 localhost:8080
npm run dev

# 小型化生产建设
npm run build

# 为生产构建并查看bundle analyzer报告
npm run build --report
```
