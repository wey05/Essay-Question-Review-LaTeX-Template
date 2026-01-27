# 《毛泽东思想和中国特色社会主义理论体系概论》论述题复习

<div align="center">

![LaTeX](https://img.shields.io/badge/LaTeX-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

一份精心整理的《毛泽东思想和中国特色社会主义理论体系概论》课程论述题复习笔记

</div>

---

## 📚 项目简介

本项目提供了一套高质量的 LaTeX 格式复习笔记，专门针对《毛泽东思想和中国特色社会主义理论体系概论》课程的论述题部分。笔记采用精美的排版设计，结构清晰，重点突出，适合考前复习使用。

### ✨ 特色功能

- **专业排版**：使用 LaTeX 专业排版系统，输出效果精美
- **结构清晰**：采用问题-答案-参考页码的结构，便于快速查找
- **重点突出**：关键知识点使用颜色标记，一目了然
- **美观设计**：精心设计的配色方案和版式，阅读体验佳
- **易于扩展**：模块化的命令设计，方便添加新的论述题

---

## 📖 内容概览

目前笔记包含以下内容：

| 题号 | 主题 | 状态 |
|------|------|------|
| 12 | "三个代表"重要思想的主要内容 | ✅ 已完成 |

更多题目正在持续更新中...

---

## 🛠️ 技术栈

- **LaTeX**：文档排版引擎
- **XeLaTeX**：推荐编译引擎（支持中文）
- **ctex**：中文支持宏包
- **tcolorbox**：精美文本框
- **fontawesome5**：图标支持

---

## 📦 安装依赖

### Windows 用户

推荐使用 TeX Live 或 MiKTeX：

```bash
# 使用 TeX Live 安装
# 下载并安装 TeX Live：https://www.tug.org/texlive/acquire-netinstall.html

# 或使用 MiKTeX
# 下载并安装 MiKTeX：https://miktex.org/download
```

### macOS 用户

推荐使用 MacTeX：

```bash
# 使用 Homebrew 安装
brew install --cask mactex
```

### Linux 用户

```bash
# Ubuntu/Debian
sudo apt-get install texlive-xetex texlive-lang-chinese

# Arch Linux
sudo pacman -S texlive-most texlive-langchinese
```

---

## 🚀 使用方法

### 编译文档

```bash
# 使用 XeLaTeX 编译（推荐）
xelatex 毛中概复习笔记.tex

# 或使用 LuaLaTeX
lualatex 毛中概复习笔记.tex

# 如果需要生成目录，需要编译两次
xelatex 毛中概复习笔记.tex
xelatex 毛中概复习笔记.tex
```

### 添加新的论述题

在文档末尾添加新的题目：

```latex
\question{题号}{题目内容}

\answer{\reference{参考页码}答案内容...}
```

---

## 📄 文档结构

```
毛中概复习笔记/
├── 毛中概复习笔记.tex    # 主文档文件
└── README.md             # 项目说明文档
```

---

## 🎨 自定义配置

### 修改颜色主题

在文档导言区修改颜色定义：

```latex
\definecolor{maincolor}{RGB}{26,60,97}        % 主色调
\definecolor{accentcolor}{RGB}{192,57,43}     % 强调色
\definecolor{secondarycolor}{RGB}{41,128,185} % 次要色
```

### 调整页面边距

```latex
\geometry{left=2.2cm,right=2.2cm,top=2.5cm,bottom=2.5cm}
```

### 修改行间距

```latex
\setstretch{1.4}  % 1.4 倍行距
```

---

## 📝 命令说明

| 命令 | 用途 | 示例 |
|------|------|------|
| `\question{编号}{内容}` | 创建论述题 | `\question{1}{题目内容}` |
| `\answer{内容}` | 创建答案 | `\answer{答案内容}` |
| `\reference{页码}` | 添加参考页码 | `\reference{课本P202}` |
| `\highlight{文本}` | 高亮文本 | `\highlight{重点内容}` |

---

## 🤝 贡献指南

欢迎提交问题和改进建议！如果您发现错误或有新的论述题想要添加，请：

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

---

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 提交 Issue
- 发送 Pull Request

---

<div align="center">

**祝您复习顺利，考试成功！** 🎓

Made with ❤️ using LaTeX

</div>
