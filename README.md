# 从零开发前端脚手架——下载GitLab模板模式
教程已发布在掘金：[从零开发前端脚手架——下载GitLab模板模式](https://juejin.cn/post/7224428335005958181)

## 本项目
是脚手架拉取的模板项目，需要根据文章内容和提示，依据自身项目需求修改相应配置才能使用。结合 [hi-cli脚手架代码](https://github.com/ShirleyZmj/hi-cli)

## 文章简介
本文主要介绍了从零开发前端脚手架的下载 GitLab 模板模式。先阐述了将基础框架配置抽成模板以提高开发效率的背景，接着详细说明了基于 GitLab 获取模板的准备步骤，包括获取访问令牌、了解相关 API 等，还给出了使用 Axios 库发送请求获取仓库信息的示例代码，以及开发过程中的优化措施，如文件夹存在判断、添加加载提示、优化提示文字等，并提供了参考代码链接。

## 项目背景
当一个团队需要同时开发多个具有相同框架和配置的项目时，为了节省搭建项目的时间，通常会将基础框架配置抽取成一个模板。当需要开设新项目时，只需要拉取该模板并配置少量的定制化参数，就可以快速进入业务开发阶段，从而大大提高了工作效率。因此，本文针对此场景设计了一个脚手架。在大多数公司中，内部使用gitlab作为协同开发工具，因此本文基于gitlab提供了相应的教程。如果使用github或gitee等其他工具，需要查阅相关资料并相应调整拉取项目的步骤。

# hi-cli-template
for template, added ask.json

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

