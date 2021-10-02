---
title: Hello World
date: 2021-09-25 21:46:02
sticky: 100
tags: 
- 新的
- 旧的
categories:
- C1
- C2
- [C3,C4]
- [C3,C5]
---

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

### 取消评论时显示浏览器内核与操作系统信息

hexo-theme-fluid/source/css/main.styl 路径下添加 (不过好像只有本地预览有效，部署到Github pages上依然不生效；在Vercel部署的，同样也已经生效了)

```css
.vmeta {
  display:none;
}
```

更好的做法是在服务端配置DISABLE_USERAGENT 环境变量为true；重新部署后得到新的server url，一定要记得把这个server url填写到_config.fluid.yml文件中，更新！！ 着了踩了个大坑！！[^2]

### Typora图床配置

[**Typora+PicGo+Github = Markdown编辑器+图床**](https://zhuanlan.zhihu.com/p/365829157)[^1]







[^1]: 牛啊
[^2]: 细心很重要



