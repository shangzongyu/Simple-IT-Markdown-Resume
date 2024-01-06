# Simple-IT-Markdown-Resume

一款适合 IT 行业的 Markdown 简约简历模版。

## 如何使用

### 准备

1. 下载编辑器工具 [Typora](https://www.typora.io/)
2. 配置简历使用的资源，打开 `Typora Settings -> Appearance -> Themes -> Open Theme Folder`，将项目 `style` 目录下文件复制到该目录下。

### 编辑简历

根据自己的需求修改 [Resume.md](Resume.md)。

### 导出简历

如果根据上面的把 css 文件放到 Themes 目录后，在 Themes 中会有两个主题 `Resume Style Avatar` 和 `Resume Style No Avatar`，选择这两个主题中一个为简历。

- Resume Style Avatar：带头像的简历样式
- Resume Style No Avatar：不带头像的简历样式

打开 Typora -> File -> Export -> PDF, 就可以了。

> - 导出没头像的需要把 `<div style="float:right;"><br><img src="assets/avatar.jpg" width="90"></div>` 去掉
> - 简历命名推荐：姓名-岗位-电话.pdf

## 目录结构

```sh
└─Simple-IT-Markdown-Resume
    │  .gitignore                                 --git 忽略文件
    │  README.md                                  --Readme 文件
    │  Resume.md                                  --简历模板
    ├─assets                                      --所有静态文件夹
    │  │  avatar.jpg
    │  │  briefcase-solid.svg
    │  │  envelope-solid.svg
    │  │  evaluate-solid.svg
    │  │  github-brands.svg
    │  │  graduation-cap-solid.svg
    │  │  honor-solid.svg
    │  │  info-circle-solid.svg
    │  │  info-solid.svg
    │  │  phone-solid.svg
    │  │  project-diagram-solid.svg
    │  │  rss-solid.svg
    │  │  tools-solid.svg
    │
    ├─result                                      --最后生成的结构
    │      resume-style-avatar.pdf
    │      resume-style-no-avatar.pdf
    │
    └─style                                       --所有简历样式文件夹
            resume-style-avatar.css
            resume-style-no-avatar.css
```

## 关于图标

因为有些 Markdown 编辑器不支持 HTML 语法，例如 Typora，也就无法导入 fontawesome 样式表。无奈之下只能将本简历模版需要使用到的图标单独下载，放入 assets 目录下，并且在简历中以 `<img>` 标签来引用，所以导出 HTML 文件若显示不正确请保证 html 文件与 assets 在同一级目录。

## 参考来源

所有资料均参考自互联网，若侵权请联系我删除。

## License

- [fontawesome](https://fontawesome.com/license)
