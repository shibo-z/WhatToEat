# WhatToEat 吃点啥
在公司天天不知道吃啥，写个程序来决定吧！

这是一个桌面应用。

---
## 构建
```text
# 安装依赖
npm install
# 编译前端页面； sencha ：ExtJs 的CMD工具
sencha app build -testing
# 打包
npm make
```

## 技术选型
```text
桌面框架；Electron
前端框架：ExtJs
```

## 目录说明
```text
main: 存放electron主进程js
renderer: 存放渲染进程js
resources: 存放electron的资源
src: ExtJs源代码
view: ExtJs编译输出目录，主进程加载此文件夹下的index.html
```