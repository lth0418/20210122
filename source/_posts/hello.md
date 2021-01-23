---
title: hello
date: 2021-01-23 09:33:45
tags:
---
创建博客文件夹

```
hexo init blog
```

安装发布工具

```
npm install hexo-deployer-git --save
```

修改配置文件

```
  theme: landscape
  
  deploy:
    type: git
    repository: 仓库地址
    branch: main
```

清除缓存

```
hexo clean
```

生成静态文件

```
hexo generate(hexo g)
```

部署

```
hexo deploy(hexo d)
```

创建博客

```
hexo new hello
```

