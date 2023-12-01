# GrainMallVue
谷粒商城前端代码
由于在网上找了很多版本的代码，发现都有点差别，最主要是"node-sass"版本有很多，踩了很多坑
于是在官网上下载了代码，项目源码下载地址 https://gitee.com/renrenio/renren-fast-vue
package.json文件中"node-sass": "^6.0.1",这位老哥（ https://zhuanlan.zhihu.com/p/656247517 ）的回答中指出了sass6.0+要用node16
并且在node16的环境下执行了两次 npm install node-sass@^6.0.1 --registry=https://registry.npm.taobao.org 才安装成功，记录一下踩的坑
