# LaTeX

## 是什么？
LaTeX是一种基于TeX的排版系统，专门用于制作高质量的科学和数学文档。它采用"所见即所想"（WYSIWYM）的方式，用户通过编写标记代码来定义文档结构和格式，系统自动处理排版细节。

## 有什么特点？
1. **专业排版**：特别适合数学公式、科学论文、技术文档的排版
2. **高质量输出**：生成PDF文档，打印质量优秀
3. **内容与格式分离**：专注于内容，系统自动处理格式
4. **强大的数学支持**：内置丰富的数学符号和公式环境
5. **引用管理**：自动处理参考文献、交叉引用、目录生成
6. **跨平台**：在Windows、macOS、Linux上均可使用
7. **开源免费**：完全免费，拥有庞大的用户社区

## 如何Getting Started？
### 安装LaTeX发行版：
1. **Windows**：安装[MiKTeX](https://miktex.org/)或[TeX Live](https://tug.org/texlive/)
2. **macOS**：安装[MacTeX](https://tug.org/mactex/)
3. **Linux**：通过包管理器安装TeX Live

### 选择编辑器：
1. **专用编辑器**：TeXstudio、TeXmaker、Overleaf（在线）
2. **通用编辑器**：VSCode + LaTeX Workshop扩展
3. **在线平台**：[Overleaf](https://www.overleaf.com/)（无需本地安装）

### 第一个LaTeX文档：
1. **创建.tex文件**：
   ```latex
   \documentclass{article}
   \usepackage[utf8]{inputenc}
   
   \title{第一个LaTeX文档}
   \author{你的名字}
   \date{\today}
   
   \begin{document}
   
   \maketitle
   
   \section{引言}
   这是我的第一个LaTeX文档！
   
   \section{数学公式}
   这是一个行内公式：$E = mc^2$
   
   这是一个显示公式：
   \[
   \int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
   \]
   
   \end{document}
   ```

2. **编译文档**：
   - 使用`pdflatex`命令编译
   - 或使用编辑器的编译按钮

3. **查看结果**：生成PDF文件并查看

### 基本语法学习：
1. **文档结构**：`\documentclass`、`\begin{document}`、`\end{document}`
2. **章节命令**：`\section`、`\subsection`、`\subsubsection`
3. **数学环境**：`$...$`（行内公式）、`\[...\]`（显示公式）
4. **列表环境**：`itemize`（无序列表）、`enumerate`（有序列表）
5. **表格和图片**：`tabular`环境、`\includegraphics`命令

## 学习资源
- Overleaf学习：[https://www.overleaf.com/learn](https://www.overleaf.com/learn)
- LaTeX教程（英文）：[https://www.latex-tutorial.com/](https://www.latex-tutorial.com/)
- LaTeX中文教程：[https://www.latexstudio.net/](https://www.latexstudio.net/)
- CTAN（LaTeX包仓库）：[https://www.ctan.org/](https://www.ctan.org/)
- LaTeX Wikibook：[https://en.wikibooks.org/wiki/LaTeX](https://en.wikibooks.org/wiki/LaTeX)

*目前内容由ai生成*