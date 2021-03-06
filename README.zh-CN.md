<p align="center">
    <a href="https://github.com/hillpy/EasyUploader/blob/master/LICENSE"><img src="https://img.shields.io/github/license/hillpy/EasyUploader.svg" alt="License"></a>
    <a href="https://www.travis-ci.com/hillpy/EasyUploader"><img src="https://img.shields.io/travis/com/hillpy/EasyUploader.svg" alt="Build Status"></a>
    <a href="https://github.com/hillpy/EasyUploader/blob/master/dist/easyuploader.min.js"><img src="https://img.shields.io/bundlephobia/min/easyuploader.svg" alt="Minfied Size"></a>
    <a href="https://www.npmjs.com/package/easyuploader"><img src="https://img.shields.io/npm/dt/easyuploader.svg" alt="Downloads"></a>
    <a href="https://github.com/hillpy/EasyUploader/releases"><img src="https://img.shields.io/github/release/hillpy/EasyUploader.svg" alt="Github Release"></a>
    <a href="https://www.npmjs.com/package/easyuploader"><img src="https://img.shields.io/npm/v/easyuploader.svg" alt="NPM Release"></a>
</p>

* [中文](./README.zh-CN.md)
* [English](./README.md)

### EasyUploader是什么

EasyUploader是一个轻量级的的js文件上传库。它基于HTML5、canvas、fileReader等技术开发。比较适合移动端使用，pc端浏览器由于HTML支持情况不同，导致使用比较受限，特别是IE浏览器，后期会考虑添加flash上传文件。它不依赖其它js库。

### 为什么要开发

文件上传在web开发中是非常常见的，现在已有的上传库也非常多（webuploader、uploaderfy等）。但是感觉还是偏重，不够轻量，而且想尽可能的掌控与熟悉源码。故萌生了想开发一款上传库的想法，考虑尽量将其做得简单实用。顺便可以学习到不少的知识（HTML5、canvas、闭包、各种工具等等）。

### 文档

[EasyUploader document](https://hillpy.github.io/EasyUploader/)

### 在线例子

[EasyUploader example](http://test.hillpy.com/easyuploader/index.html)

### 特性

* 文件上传
* 图片压缩
* 拖曳上传
* 照片上传旋转修正

### 备注

项目正在开发中。发布的暂时还是测试版本。我很抱歉我的英语比较烂。关于项目问题，请在[github issue](https://github.com/hillpy/EasyUploader/issues "github issue")提交即可。如果亲能赏个star，我会非常高兴的。

### 如何安装

* 使用NPM方式

    ```
    npm install easyuploader --save
    ```

* 使用script (unpkg CDN)方式.

    ```
    <script src="https://unpkg.com/easyuploader/dist/easyuploader.min.js"></script>
    ```

### 如何运行

* 运行项目

    1. 克隆本项目

        ```
        git clone https://github.com/hillpy/EasyUploader.git
        ```

    2. 安装node依赖包

        ```
        npm install
        ```

    3. 开启rollup监听及web服务（需php环境），url：localhost:1180/example/index.html。

        ```
        npm run dev
        ```

    4. 打包构建

        ```
        npm run build
        ```

* 运行文档

    1. 全局安装gitbook-cli

        ```
        npm install gitbook-cli -g
        ```

    2. 安装依赖库

        ```
        cd doc && gitbook install
        ```

    3. 启动服务

        ```
        gitbook serve
        ```

### 版本日志

[版本日志](https://github.com/hillpy/EasyUploader/releases)

### 待做

~~1. 避免创建的input中id属性出现冲突~~

~~2. 限制文件上传类型~~

3. 多文件上传

4. 图片裁剪

5. 断点续传、文件分片上传

### 仓库链接

[Github](https://github.com/hillpy/EasyUploader "EasyUploader")<br>
[Gitee](https://gitee.com/hillpy/EasyUploader "EasyUploader")<br>

### 协议

[MIT](https://github.com/hillpy/EasyUploader/blob/master/LICENSE "MIT")<br>