<h1 align="center">
  <img src="public/mark.svg" alt="" width="88" height="88">
  <br>
  Boron
</h1>

<p align="center">精美、可编辑的终端截图。</p>

<p align="center"><a href="https://boron.sh"><b>boron.sh</b></a></p>

<p align="center">
  <img src="docs/app.png" alt="Boron 编辑器：渐变背景上的终端区块，侧边栏包含主题、背景和窗口设置">
</p>

## 功能特性

- **粘贴真实输出并保留颜色。** 完整解析 ANSI 转义码，包括 256 色和真彩色；对于支持富文本复制的终端，也会读取剪贴板中的样式。
- **像编辑文档一样修改。** 选择任意文本片段即可重新着色，也可以直接输入内容。颜色使用 Chalk 的十六个名称而不是十六进制值，因此切换主题时会自动映射。
- **选择整列，而不只是文本片段。** 终端输出是一个网格，因此需要修改的内容常常是纵向的——表格的一列、`tree` 的缩进线或左侧的时间戳。按住 Alt 拖动（Mac 上为 ⌥）即可绘制矩形区域，并精确地重新着色、删除或复制每一行的这些单元格。
- **命令行高亮，输出淡化。** 以 `$`、`❯`、单独的 `>` 或 oh-my-zsh 的 `➜` 开头的行会被识别为命令，其余内容则淡化显示。
- **八种主题** —— Boron、VS Code 深色+、德古拉、东京之夜、Catppuccin 摩卡、Nord 极地、One Dark 深色、Solarized 深色。
- **导出 PNG、SVG、JPEG 或 WebP**，也可以直接将图片复制到剪贴板。
- **复制为文本** —— 原始 ANSI、可运行的 Chalk 代码片段或纯文本。可以先设计程序输出的效果，再把转义序列交给开发者。

<p align="center">
  <img src="public/example.png" alt="导出的终端区块：开发服务器启动中，含彩色提示符、下划线链接、填充的项目名和绿色 READY 徽章">
</p>

Boron 绘制的所有内容都能在真实终端中表示。调色板是 Chalk 的十六种颜色，修饰符是 Chalk 的修饰符，自动样式也表达为 Chalk 标记而不是手挑的十六进制值，因此你制作的图片与复制出来的转义序列是同一件事。

开发说明见 [AGENTS.md](AGENTS.md)。

立即体验 👉 [https://boron.sh](https://boron.sh)
