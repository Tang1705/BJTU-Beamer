<h1 align="center">
  <a href="https://github.com/Tang1705/BJTU-Bachelor-Thesis" title="Bachelor Thesis LaTeX Template for Beijing Jiaotong University">
    <img alt="BJTU-Bachelor-Thesis" src="preview/icon.png" width="75%" />
  </a>
  <br />
  北京交通大学 Beamer 主题
</h1>
<p align="center">
Beamer Theme for Beijing Jiaotong University
</p>

## 📝 repo 介绍

## 📑 使用说明

1. 下载这个项目的 zip 包到到本地
2. 直接对 chapters 文件下的 tex 文件进行修改，对应的摘要、章节内容、附录文件均已经默认生成，在此基础上加以修改即可
3. 替换 reference/bjtu-bachelor-thesis-reference.bib 内容为论文需要的 bibtex 参考文献
4. 请使用XeLaTeX编译
5. *make samplebib & Enjoy*

## 📁 文件结构

<details>
  <summary>BJTU-Bachelor-Thesis</summary>
    <details>
        <summary>bjtu-bachelor-thesis</summary>

- chapters 正文各章节 tex 文件
- figures 论文插图
- reference 参考文献
- vi 视觉识别/校徽
- font 字体文件
- word word 模板
- bjtu-bachelor-thesis.cls 样式模板
- main.tex
- main.pdf
    </details>
    <details>
        <summary>example</summary>
使用示例，包括多图排列、表格跨页等
    </details>
    <details>
        <summary>sample</summary>
论文排版样例
    </details>
</details>

|       |                   展示                   |                       展示                        |
  |:--------------------------------------:|:-----------------------------------------------:| :-----------------------------------------------: |
  | 预览  |  ![coverpage](preview/coverpage.png)   | ![frontpage_chs](preview/authorizationpage.png) |
  | 说明  |                  封面页                   |                       授权页                       |
  | 文件  |              `\makecover`              |              `\makeAuthorization`               |
  | 预览  | ![frontpage_eng](preview/abstract.png) |    ![abstract_chs](preview/abstract_en.png)     |
  | 说明  |                  中文摘要                  |                      英文摘要                       |
  | 文件  |             `abstract.tex`             |              `englishabstract.tex`              |
  | 预览  |  ![abstract_eng](preview/content.png)  |       ![references](preview/chapter.png)        |
  | 说明  |                   目录                   |                     正文（部分）                      |
  | 文件  |           `\tableofcontents`           |                   `chapters/`                   |
  | 预览  |   ![appendix](preview/reference.png)   |     ![acknowledgements](preview/thanks.png)     |
  | 说明  |                  参考文献                  |                       致谢                        |
  | 文件  |  `bjtu-bachelor-thesis-reference.bib`  |                  `thanks.tex`                   |
  | 预览  |    ![mywork](preview/appendix.png)     |         ![statement](preview/main.png)          |
  | 说明  |                   附录                   |                     论文模板预览                      |
  | 文件  |             `appendix.tex`             |                   `main.pdf`                    |