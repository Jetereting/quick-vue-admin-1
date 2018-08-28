<p align="center">
  <h1>quick-vue-admin</h1>
</p>

English | [简体中文](./README.zh-CN.md)

# 介绍

quick-vue-admi是一个开箱即用的后台集成解决方案，它基于[Vue](https://cn.vuejs.org/)、[Element](http://element-cn.eleme.io)和[MongoDB](https://www.mongodb.com/)，开创性地t推出基于配置的开发解决方案，帮你最快速地搭建企业级后台产品.

 - [使用文档](https://linzhixian.github.io/quick-vue-admin-document)
  
 - 演示
 https://linzhixian.github.io/element-vue-admin
 
## Dependencies
- nodejs &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(need stand alone install)
- koa 2.0.0  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(include)
- Element UI 2.x &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(include)
- MongoDB 3.x &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(need stand alone install)

## Features
```
- Login / Logout

- Permission Authentication
  - Menu permission
  - User Role permission

- CRUD CONFIG
  - through create one meta config file to auto generate CRUD page
  - auto create collection in MongoDB
  - auto create index in MongoDB
 

- Error Page
  - 401
  - 404
```

## Getting started

```bash
# clone the project
git clone https://github.com/linzhixian/quick-vue-admin.git

# install dependency
npm install

# develop
npm run dev
```

Open browser on： http://localhost:9001.

## Build
```bash
# build for production environment
npm run build
```
## Run
```bash
# Run for development environment
npm run dev
# Run for production environment
npm run pm2
```

## License

[MIT](https://github.com/linzhixian/quick-vue-admin/blob/master/LICENSE)

Copyright (c) 2018-present ZhiXianLin
