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

BJTUBeamer 主题为作者基于本科毕业设计中使用的 PPT 模板制作，旨在提供对应风格的 Beamer 制作方式，可用于学位答辩、课堂演示、学术交流或其他需要演示文稿 的活动，方便地使用 LaTeX 制作含有学校特色的演示文稿。

## 📑 使用说明

1. 下载这个项目的 zip 包到到本地
2. 直接对 bjtubeamer/main.tex 文件进行修改
3. 请使用XeLaTeX编译
4. *make samplebib & Enjoy*

## 📁 文件结构

<details>
  <summary>BJTU-Beamer</summary>
    <details>
        <summary>bjtubeamer</summary>

- beamerthemebjtubeamer.sty 演示主题
- beamerinnerthemebjtubeamer.sty 内部主题
- beamerouterthemebjtubeamer.sty 外部主题
- beamercolorthemebjtubeamer.sty 色彩主题
- beamerfontthemebjtubeamer.sty 字体主题
- resources 主题相关素材
- figures 插图
- main.tex 
- main.pdf
- bjtubeamer.tex
- bjtubeamer.pdf 用户手册

    </details>
    <details>
        <summary>sample</summary>
slide 排版样例
    </details>
</details>

|       |                 展示                  |                       展示                       |
  |:-----------------------------------:|:----------------------------------------------:| :-----------------------------------------------: |
  | 预览  | ![coverpage](preview/coverpage.png) |   ![sectioncover](preview/sectioncover1.png)   |
  | 说明  |                 封面页                 |                    章节封面（1）                     |
  | 文件  |            `\makecover`             |                  `\section{}`                  |
  | 预览  | ![contentpage](preview/content.png) |   ![sectioncover](preview/sectioncover2.png)   |
  | 说明  |                 目录页                 |                    章节封面（2）                     |
  | 文件  |           `\makecontent`            |                  `\section{}`                  |
  | 预览  |     ![frame](preview/frame.png)     |    ![sectioncover](preview/sectioncover3.png)    |
  | 说明  |                 内容帧                 |                    章节封面（3）                     |
  | 文件  |    `\begin{frame}……\end{frame}`     |                  `\section{}`                  |
  | 预览  | ![backcover](preview/backcover.png) | ![sectioncover](preview/sectioncover4.png) |
  | 说明  |                 封底                  |                    章节封面（4）                     |
  | 文件  |          `\makebackcover`           |                  `\section{}`                  |
  | 预览  |     ![beamer](preview/main.png)     |    ![sectioncover](preview/sectioncover5.png)     |
  | 说明  |             Beamer 主题预览             |                    章节封面（5）                     |
  | 文件  |             `main.pdf`              |                  `\section{}`                  |
