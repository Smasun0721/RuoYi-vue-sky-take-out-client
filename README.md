# 苍穹外卖课程项目（RuoYi 前端）

![Vue](https://img.shields.io/badge/Vue-3-42B883?logo=vue.js&logoColor=white)
![Vite](https://img.shields.io/badge/Build-Vite-646CFF?logo=vite&logoColor=white)
![Element Plus](https://img.shields.io/badge/UI-Element%20Plus-409EFF)
![RuoYi](https://img.shields.io/badge/Framework-RuoYi%203.8.7-4B6BFB)

基于 RuoYi-Vue 3.8.7 的苍穹外卖课程项目前端初始化版本，包含登录、权限菜单、系统管理和基础页面布局。

## 功能范围

- 登录、验证码、权限菜单
- 用户、角色、菜单、部门管理
- 字典、参数、通知公告
- 系统监控与日志页面
- 基于 Vue 3 + Element Plus 的后台布局

## 技术栈

- Vue 3、Vite
- Element Plus、Vue Router、Pinia
- Axios、ECharts
- RuoYi-Vue 3.8.7

## 环境要求

- Node.js 18+
- npm 或 pnpm

## 安装与启动

~~~bash
git clone https://github.com/Smasun0721/RuoYi-vue-sky-take-out-client.git
cd RuoYi-vue-sky-take-out-client
npm install
npm run dev
~~~

后端地址通过 VITE_APP_BASE_API=/dev-api 代理，具体配置见 .env.development 和 vite.config.js。

## 关联仓库

- 服务端：[RuoYi-vue-sky-take-out-server](https://github.com/Smasun0721/RuoYi-vue-sky-take-out-server)

## 说明

本项目是课程项目的初始化版本，保留 RuoYi-Vue 原始结构和基础页面；外卖业务页面在此基础上继续开发。
