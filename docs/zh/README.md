<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/wordmark-light.png" width="300" alt="DigSearch"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <b>中文</b> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a></p>

<p align="center">Excel、Word、PowerPoint、PDF、扫描文档和文本文件：成千上万文件中的每一行，边输入边找到。完全在您的电脑上运行。</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/zh/search.svg" width="840" alt="在文件内容中搜索"></p>

<p align="center">✓ 单个文件，无需安装 &nbsp;·&nbsp; ✓ 不联网，数据留在本机 &nbsp;·&nbsp; ✓ Windows · Linux · macOS</p>

<p align="center"><a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe"><b>Windows</b></a> <sub>.exe</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msi"><b>Windows</b></a> <sub>.msi</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.dmg"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.dmg"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **2,500** | **14 秒** | **4–50 ms** | **30+** | **5** |
|:---:|:---:|:---:|:---:|:---:|
| 个文件，260 万行 | 首次索引 | 选择性搜索 | 种文件类型 | 种语言：TR · EN · DE · 中文 · RU |

## 工作原理

1. **添加文件夹** — 选定文件夹后先绘出地图：各子文件夹占多少空间、有哪些类型。用复选框选择要搜索的部分。
2. **建立索引** — 用全部核心读取文件，文本压缩后写入磁盘索引。2,500 个文件、260 万行约需 14 秒。
3. **边输入边搜索** — 每次按键刷新结果，附带匹配行数、文件数和类型数。选中的行在预览中打开并滚动到位。

### 每个字符都在缩小范围

![每个字符都在缩小范围](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/zh/typing.svg)

_输入时匹配数逐步缩小：每个字符都减少候选块。_

## 功能

### 在文件内容中搜索

Excel 单元格、Word 段落和表格、PowerPoint 幻灯片、PDF 页面、文本和代码文件。多个词找同时包含全部的行；引号表示“精确短语”。

> 机柜 3 → **机柜 3** 机房 · 12 台服务器

### 扫描文档的 OCR

读取没有文本层的 PDF 页面和图片（JPG、PNG、TIFF）。已读页面会保留，不再重复读取。

### 按文件和文件夹名搜索

一键只搜索名称：一个字符就够。* 代表任意一个字符。文件夹也会列出，带修改和创建日期。

> 报告_202* → 报告_202**5**.xlsx · 报告_202**6**.docx

![按文件和文件夹名搜索](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/zh/names.svg)

### 默认宽松，需要时精确

默认不区分大小写和重音。Aa 区分大小写，ab 仅整词，.* 正则表达式。可关闭即时搜索，改为按 Enter。

### 层级或列表，由您定义

结果按文件分组，或每个匹配一行。选择列、拖动排序、边缘调宽、双击适应。每列有“包含 / 不包含”筛选。

### 导出为 Excel 或 CSV

显示的列和筛选后的行，每个匹配一行：xlsx（加粗表头、冻结首行）或 UTF-8 CSV，通过系统保存对话框。

### 原位预览

选中文件在右侧打开并滚动到匹配处；滚动时继续加载。Excel 工作表为选项卡，表格带表头。文件内查找、复制行或表、在编辑器中打开。

### 文件夹分析

可缩放的大小地图、重复文件、大文件和旧文件、大小 × 年龄图。勾选的文件可移到回收站。

### 自动跟踪变化

监视的文件夹中，新增、更改和删除的文件几秒内进入索引。未监视的文件夹在启动时和需要时扫描。

### 百万行中的毫秒级

文本保存在分块索引中，搜索只读取候选块。260 万行中的选择性搜索 4–50 ms。内存和 CPU 用量随机器调整。

### 一切都在您的电脑上

不联网、无需账户、不发送任何数据。索引和设置在本地文件夹，卸载即删除。

### 五种语言，键盘优先

Türkçe、English、Deutsch、中文、Русский。/ 聚焦搜索框，↑↓ 浏览匹配，Ctrl+K 打开分析，Ctrl+Enter 打开文件。

## 可读取的文件类型

也可以添加自己的扩展名，按纯文本逐行读取。不需要的类型可按文件夹关闭。

| | |
|---|---|
| **办公** | `.xlsx` `.xlsm` `.docx` `.docm` `.pptx` `.rtf` `.odt` `.ods` `.odp` |
| **PDF 与电子书** | `.pdf` `.epub` |
| **数据** | `.csv` `.tsv` `.json` `.xml` `.yaml` `.toml` `.ini` `.sql` |
| **代码** | `.go` `.py` `.js` `.ts` `.java` `.cs` `.c` `.cpp` `.ps1` `.bat` `.sh` |
| **网页与文本** | `.txt` `.log` `.md` `.html` `.css` `.conf` `.cfg` |
| **邮件与联系人** | `.eml` `.msg` `.vcf` |
| **图片 (OCR)** | `.jpg` `.png` `.tif` `.bmp` `.gif` `.webp` |

## 下载

版本 1.0.0 · 单个文件：下载即可运行。索引和设置只保存在本机；卸载时全部删除。

**Windows** — `digsearch-1.0.0.exe · ~59 MB`

- Windows 10 / 11，64 位
- Exe：无需安装和管理员权限；也可选 MSI 安装程序
- 内置 PDF 读取和 OCR

[⤓ 下载 Windows 版](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe) &nbsp;·&nbsp; [⤓ MSI](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msi)

**macOS** — `digsearch-1.0.0-macos-arm64.dmg · digsearch-1.0.0-macos-amd64.dmg`

- Apple Silicon（M1 及以后）或 Intel；打开 DMG，把应用拖到"应用程序"
- 未签名：若 macOS 提示无法打开，请到 系统设置 › 隐私与安全性 › 仍要打开；或在终端运行 `xattr -cr /Applications/DigSearch.app`
- 内置 PDF 读取和 OCR

[⤓ Apple Silicon](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.dmg) &nbsp;·&nbsp; [⤓ Intel](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.dmg)

**Linux** — `digsearch-1.0.0-linux-amd64 · ~55 MB`

- x86-64，单个文件：下载后执行 `chmod +x digsearch-1.0.0-linux-amd64` 再运行
- 窗口使用 Chrome、Chromium、Edge 或 Brave；否则在浏览器中打开
- 内置 PDF 读取和 OCR

[⤓ Linux amd64](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64)

---

DigSearch 不联网、无需账户、不发送任何数据。PDF 读取使用 MuPDF（AGPL），OCR 使用 Tesseract。

© 2026 Mehmet Göğebakan
