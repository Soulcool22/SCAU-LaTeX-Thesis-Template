# SCAU LaTeX Thesis Template (SCAU-LaTeX-Thesis-Template)

[![LaTeX](https://img.shields.io/badge/LaTeX-Project-blue.svg?style=flat-square&logo=latex)](https://www.latex-project.org/)
[![License](https://img.shields.io/badge/License-LPPL%201.3c-lightgrey.svg?style=flat-square)](https://www.latex-project.org/lppl.txt)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-blue.svg?style=flat-square)](https://github.com/Soulcool22/SCAU-LaTeX-Thesis-Template/graphs/commit-activity)

---

## 特性 (Features)

* **符合校规**：遵循华南农业大学本科生毕业论文写作规范。
* **排版精美**：中英文双语摘要、三线表、完美公式支持、全自动目录。
* **代码友好**：内置 Python, JavaScript, C, C++ 等主流编程语言的高亮方案，适合理工科及信息类专业。
* **文献标准**：集成 `gbt7714` 宏包，自动生成符合 GB/T 7714-2015 标准的作者-年份制参考文献。
* **现代流程**：推荐使用 XeLaTeX 编译，支持现代中文字体系统，编译速度快。

---

## 环境准备 (Prerequisites)

1. **TeX 发行版**：安装 [TeX Live](https://tug.org/texlive/) (推荐) 或 MiKTeX。
2. **编译引擎**：必须使用 **XeLaTeX**。
3. **编辑器**：推荐 VS Code (配合 LaTeX Workshop 插件) 或 TeXstudio。

---

## 快速开始 (Quick Start)

### 1. 克隆 / 下载项目

```bash
git clone https://github.com/Soulcool22/SCAU-LaTeX-Thesis-Template.git
cd SCAU-LaTeX-Thesis-Template
```

### 2. 编译论文

使用 `latexmk` 可以自动处理交叉引用和参考文献，最为推荐：

```bash
latexmk -xelatex thesis.tex
```

*或者在 IDE 中将编译器设置为 `XeLaTeX`。*

---

## 如何自定义 (How to Customize)

大部分个人信息和内容都在 `thesis.tex` 中进行配置：

1. **配置个人信息** (约第 58 行)：

   ```latex
   \newcommand{\thesisTitle}{你的论文题目}
   \newcommand{\yourDept}{学院名称}
   \newcommand{\yourMajor}{专业名称}
   \newcommand{\yourName}{姓名}
   \newcommand{\yourMentor}{导师姓名}
   \newcommand{\yourjob}{职称}
   \newcommand{\studentID}{学号}
   ```
2. **撰写正文**：直接在 `thesis.tex` 的各 `\section` 下填写内容。
3. **管理文献**：在 `references.bib` 中填入 BibTeX 格式的参考文献。

---

## 项目结构 (Project Structure)

```text
.
├── thesis.tex          # 论文主文件（在此修改内容）
├── SCAU.cls            # 论文类样式文件（定义排版逻辑）
├── references.bib      # 参考文献数据库
├── SCAU1.png           # 学校 Logo 图片
├── Fig/                # 图片文件夹
│   └── latex.jpg       # 图片示例
└── README.md           # 本文件
```

---

## 鸣谢 (Acknowledgements)

* **原有贡献者**：感谢 `残橘子` 学长在 Overleaf 上发布的版本。
* **AI 辅助**：感谢 **Antigravity**、**Claude Code** 以及 **Codex** 等 AI 在板式调优、宏包冲突解决中的大力协助。
* **维护者**：[JohntanX](https://github.com/Soulcool22)。

---

## 联系与反馈 (Contact)

如果您在使用过程中遇到任何问题，欢迎：

* 在 GitHub 上提 **Issue** 或发起 **Pull Request**。
* 关注作者：[Soulcool22 (JohntanX)](https://github.com/Soulcool22)。
* 交流邮件：`1391861399@qq.com`。

---

> 如果这个模板对你有帮助，欢迎点个 **Star** 鼓励一下作者！祝同学们顺利毕业！

