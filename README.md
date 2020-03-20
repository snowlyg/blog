## 生活中的难过

> 使用 [hugo](https://www.gohugo.org/) 框架开发的静态博客站点
>

##### 克隆代码
```shell script
  # github
  git clone https://github.com/snowlyg/blog.git --depth 1

  # gitee
  git clone https://gitee.com/snowlyg/blog.git --depth 1
```

##### 增加内容
```shell script
  # 增加文章
  hugo new /posts/new.md 
```

##### 启动项目
```shell script
  # 开发
  hugo server   -D

  # 部署
  hugo  -b "http://coderzh.github.io/"
```