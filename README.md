# Design-Doc

原型图与设计文档仓库，按项目分文件夹管理。

## 📂 项目列表

| 项目 | 说明 | 在线预览 |
|------|------|---------|
| [DAR](./DAR/) | DAR 项目原型图 | [打开](https://vivian12139-wisc.github.io/Design-Doc/DAR/) |
| [yimian](./yimian/) | 易面项目原型图 | [打开](https://vivian12139-wisc.github.io/Design-Doc/yimian/) |

## 🗂 目录结构

```
Design-Doc/
├── README.md              本文件
├── .gitignore
├── DAR/                   项目 1
│   ├── index.html         导航入口
│   └── *.html             各原型页面
└── yimian/                项目 2
    ├── index.html
    └── *.html
```

## 🚀 在线预览

本仓库已启用 GitHub Pages,所有 HTML 原型可直接在浏览器打开查看:

👉 https://vivian12139-wisc.github.io/Design-Doc/

## 📝 更新方式

```bash
# 添加新项目或更新文件后
git add .
git commit -m "更新说明"
git push
```

## ✏️ 新增项目

1. 在仓库根目录新建文件夹 `项目名/`(建议英文或拼音)
2. 把原型 HTML 放进去
3. 创建 `index.html` 作为导航入口
4. 更新本 README 的项目列表
