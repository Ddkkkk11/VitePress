---
layout: doc
title: 'Tools'
---
# 一些工具
## 博客相关
- [免费快速的图床](https://tucdn.wpon.cn/)
## 表格组件
- [gridmanager组件官网](https://gridmanager.lovejavascript.com/api/index.html)
## 插画图
- [插画图地址](https://undraw.co/illustrations)
## css布局小样式
- [地址](https://uiverse.io/)
## 生成树结构小工具
- [tree-node-cli](https://github.com/yangshun/tree-node-cli#readme)
![tree](https://tucdn.wpon.cn/2023/02/22/2e7d7cbb52fc3.png)

看起来目录是不是清晰很多?
```markdown
首先安装一下这个小工具
npm install -g tree-node-cli
或者
npm install --global tree-node-cli
```

```markdown
使用git bash打开命令行
tree -h 查看一些tree命令的参数
```
```markdown
tree -L n 显示项目的层级。n表示层级数。
如果你想显示两层的目录结构
tree -L 2即可
如果你过滤掉不想显示的目录,可以使用这个命令
tree -I pattern 
比如你想过滤掉node-modules和public这个目录
tree -I "node_modules|public"
```
```markdown
如果既想显示两层的目录结构,又想过滤掉如node_modules这样的文件
tree -L 2 -I "node_modules | public"
```
```markdown
最后想输出到readme.md上可以
tree -L 2 -I "node_modules" > readme.md
就可以得到上面图片显示的结果啦
```
