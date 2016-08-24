# mvproject.project.webpack1
================

## 构建环境

进入工作目录

将燕尾服源码clone到本地

进入燕尾服目录`cd stc`，执行`sh update.sh`，完成燕尾服初始化

## 构建编译

运行命令`sh build.sh`，输出目录`output/`

## webpack 环境初始化

运行命令 `sh init_webpack.sh` 初始化 npm package.json 和 bower.json 配置的组件

## 静态资源说明

除了 js 和 html, 原有的 css、img 结构不变

js 的开发目录将改为 src-webpack/static 目录下面的js
src-webpack/static/js 里面的文件 webpack 编译后将实时保存到 src/static/js 目录下对应的文件

html 的开发目录将改为 src-webpack/目录下面的html文件
src-webpack/*.html 文件 webpack 编译后将实时保存到 src/*.html 

## 使用 webpack
    
实时编译命令 `webpack --watch`

如果发现文件更改后内容没有更新，请重新运行命令 `webpack --watch` (目前该问题存在于个别文件系统)

## pc 站点的 webpack 改动示例

请查看 分支 `0.2`

## webpack cdn 发布说明

资源发布还是使用原有的 stc 发布方法


