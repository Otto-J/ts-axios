---
title: ts+axios 笔记
date: 2019-12-14 16:18:43
---

从ts才零开始实现一个axios库。

# 安装

```shell
npm i -g typescript
tsc -V
```
# 基本概念

略

# 项目构建

# 特点

- 在浏览器端使用 XMLHttpRequest 对象通讯
- 支持 Promise API
- 支持请求和响应的拦截器
- 支持请求数据和响应数据的转换
- 支持请求的取消
- JSON 数据的自动转换
- 客户端防止 XSRF

## 初始化项目


搭架子使用 [typescript-library-starter](https://github.com/alexjoverm/typescript-library-starter)

克隆并运行即可。

提交这里很有意思，不允许使用：

```shell
git commit -m 'xxx'

# 执行的是

yarn commit
```