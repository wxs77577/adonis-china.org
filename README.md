# AdonisJs China官网源码


本项目为AdonisJs中文站[adonis-china.org](http://adonis-china.org)的官方仓库，您可以自由下载并在本地运行文档。

# 翻译流程
> 本翻译仅限网站文字内容翻译，文档翻译请移步[AdonisJs中文文档](https://github.com/wxs77577/docs/tree/4.1-zh)
1. [提交一个Issue](https://github.com/wxs77577/adonis-china.org/issues/new)，告知翻译的部分
2. Fork 到自己的账号后修改提交并发送PullRequest

<img src="https://res.cloudinary.com/adonisjs/image/upload/q_100/v1497112678/adonis-purple_pzkmzt.svg" width="150px" align="right">

## 安装
> 请确保已安装`adonis`命令行工具

```bash
git clone --recursive https://github.com/wxs77577/adonis-china.org.git
cd adonis-china.org
code .
cnpm i
```

复制 `.env.example` 到 `.env`

```bash
adonis key:generate
adonis serve --dev
```

## 实时编译文档

```bash
adonis compile:docs --watch
```

## 编译样式


```bash
npm run compile:styles

# 实时编译
npm run styles
```

## 编译js

```js
npm run compile:scripts

# 实时编译
npm run scripts
```
