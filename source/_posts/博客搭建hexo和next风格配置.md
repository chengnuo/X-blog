---
title: 博客搭建hexo和next风格配置
date: 2017-07-03 14:00:47
category: hexo
---

## 快速启动

### 进入hexo中文官网页面

``` bash
https://hexo.io/zh-cn/
```

### 控制台输入

``` bash
$ npm install hexo-cli -g
$ hexo init blog
$ cd blog
$ npm install
$ hexo generate
$ hexo server
```

### 成功后在浏览器打开页面
``` bash
http://localhost:4000/
```

## 文章
### 写一篇文章

``` bash
$ hexo new "My New Post"
```

更多: [写作](https://hexo.io/zh-cn/docs/writing.html)

### 启动服务

``` bash
$ hexo server
```

更多: [服务](https://hexo.io/zh-cn/docs/server.html)

### 生成静态文件

``` bash
$ hexo generate
```

更多: [生成文件](https://hexo.io/zh-cn/docs/generating.html)

### 部署

``` bash
$ hexo deploy
```

更多: [部署](https://hexo.io/zh-cn/docs/deployment.html)


## Next主题

### 下载
``` bash
$ cd hexo根目录package.json那个目录
$ git clone https://github.com/iissnan/hexo-theme-next themes/next
```
### 配置
需要修改/root/_config.yml配置项theme：
``` bash
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: next
```
### 验证是否启用
``` bash
$ hexo s --debug
```


## 参考文档
hexo 中文网 [https://hexo.io/zh-cn/docs/](https://hexo.io/zh-cn/docs/)
next 风格 [http://theme-next.iissnan.com/](http://theme-next.iissnan.com/)
Hexo 主题使用进阶 [http://blog.csdn.net/lsshlsw/article/details/50322465](http://blog.csdn.net/lsshlsw/article/details/50322465)
hexo [常见问题解决方案](http://wp.huangshiyang.com/hexo%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88)
