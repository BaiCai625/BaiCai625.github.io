[![BaiCai625](https://img.shields.io/badge/BaiCai625-Github-blue?logo=github)](https://github.com/BaiCai625)

# 个人主页（BaiCai625.github.io）

本项目是 Xianghui Li 的个人学术与职业主页，基于 GitHub Pages 搭建，支持响应式设计和多终端浏览。主页内容涵盖了我的基本信息、学术成果、获奖情况、任职经历、专利等，旨在为学术交流、职业展示和个人品牌建设提供一个简洁美观的平台。

## 主要特色
- **简洁现代的 UI**：采用苹果风格的毛玻璃卡片设计，整体风格清新、专业。
- **内容结构清晰**：分为首页、论文发表、获奖、任职经历、专利等多个板块，信息一目了然。
- **自动化内容加载**：各板块内容通过 Markdown 文件维护，便于更新和管理。
- **自适应布局**：兼容 PC 和移动端，浏览体验一致。

欢迎访问我的主页，了解更多个人信息与学术成果。

---

## Preview
[![Screenshot of the Website](https://github.com/BaiCai625/BaiCai625.github.io/blob/main/screenshot_full.png)](https://github.com/BaiCai625)


## Introduction

This personal academic website template is based on [bootstrap](https://github.com/StartBootstrap/startbootstrap-new-age).

The template is designed to integrate Markdown files as content input.  There's no need to compile the webpage before deployment.  Upon loading, the Markdown files are automatically parsed and embedded into the page.

This template supports LaTeX formula input. You can use `$...$` and `\(...\)` as delimiters for inline-math, or use `$$...$$` and `\[...\]` as delimiters for display-math. Macros such as `\ref{...}`, `\eqref{...}`, and `\begin{equation}...\end{equation}` are also supported. See [MathJax](https://docs.mathjax.org/en/latest/index.html) for more details.

:milky_way: Demo: https://baicai625.github.io/


## Getting Start
### 1. Fork this repository
The repository name should be `<username>.github.io`, which will also be your website's URL.


### 2. Edit page content

(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Modify the content of each section, which corresponds to `contents/*.md`.

(3) Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) Push it: 
```
git commit -am 'init'
git push
```


### 3. Enjoy

Fire up a browser and go to `https://<username>.github.io`



## License

Copyright Xianghui Li, 2025. Adapted from theme created by Sen Li. Licensed under an MIT license. You can copy and mess with this template.
