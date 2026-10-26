<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/wordmark-light.png" width="300" alt="DigSearch"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <b>English</b> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a> &nbsp;·&nbsp; <a href="../../docs/ru/README.md">Русский</a></p>

<p align="center">Excel, Word, PowerPoint, PDF, scanned documents and text files: every line inside thousands of files is found as you type. Runs entirely on your computer.</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/en/search.svg" width="840" alt="Search inside files"></p>

<p align="center">✓ One file, no installer &nbsp;·&nbsp; ✓ No internet, data stays with you &nbsp;·&nbsp; ✓ Windows · Linux · macOS</p>

<p align="center"><a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe"><b>Windows</b></a> <sub>.exe</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msi"><b>Windows</b></a> <sub>.msi</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.dmg"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.dmg"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **2,500** | **14 s** | **4–50 ms** | **30+** | **5** |
|:---:|:---:|:---:|:---:|:---:|
| files, 2.6 M lines | first index | a selective search | file types | languages: TR · EN · DE · 中文 · RU |

## How it works

1. **Add a folder** — Choosing a folder draws a map before anything is read: how much each subfolder takes, which types it holds. Tick what goes into the search.
2. **The index is built** — Files are read on all cores and the text goes into a compressed index on disk. 2,500 files and 2.6 million lines take about 14 seconds.
3. **Search as you type** — Results refresh on every key, with counts of matching lines, files and types. The selected line opens in the preview and scrolls into view.

### Every letter narrows it down

![Every letter narrows it down](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/en/typing.svg)

_The count narrows as you type: every letter cuts the candidate blocks down._

## Features

### Search inside files

Excel cells, Word paragraphs and tables, PowerPoint slides, PDF pages, text and code files. Several words find the lines with all of them; "exact phrase" with quotes.

> rack 3 → **Rack 3** server room · 12 servers

### OCR for scanned documents

PDF pages without a text layer and images (JPG, PNG, TIFF) are read. Pages once read are kept and never read again.

### Search in file and folder names

One button searches names only: a single letter is enough. * stands for one character. Folders are listed too, with their modified and created dates.

> report_202* → report_202**5**.xlsx · report_202**6**.docx

![Search in file and folder names](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@e2896792122f/assets/screens/en/names.svg)

### Relaxed by default, exact when you want

By default case and accents do not matter. Aa makes it case-sensitive, ab whole words only, .* regular expressions. Live search can be turned off to search on Enter.

### Hierarchy or list, your table

Results group by file or every match becomes a row. Pick columns, drag them into order, resize at the edge, double-click to fit. A contains / does not contain filter per column.

### Export to Excel or CSV

The shown columns and filtered rows, one row per match: xlsx (bold header, frozen first row) or UTF-8 CSV, through the system save dialog.

### Preview in place

The selected file opens on the right and scrolls to the match; more loads as you scroll. Excel sheets as tabs, tables with headers. Find in file, copy a row or table, open in the editor.

### Folder Analysis

A zoomable size map, duplicate files, large and old files, a size × age map. Move what you tick to the Recycle Bin.

### Changes on their own

In a watched folder, added, changed and deleted files reach the index within seconds. Unwatched folders are scanned at start and on request.

### Milliseconds across millions of lines

Text lives in an index of blocks; a search reads only the candidate blocks. A selective search over 2.6 million lines takes 4–50 ms. Memory and CPU use adapt to your machine.

### Everything on your computer

No internet, no account, nothing is sent anywhere. The index and settings sit in a local folder and go when you uninstall.

### Five languages, keyboard first

Türkçe, English, Deutsch, 中文, Русский. / focuses the search box, ↑↓ walk the matches, Ctrl+K opens analysis, Ctrl+Enter opens the file.

## File types read

Add your own extensions too; they are read line by line as plain text. Types you do not want can be switched off per folder.

| | |
|---|---|
| **Office** | `.xlsx` `.xlsm` `.docx` `.docm` `.pptx` `.rtf` `.odt` `.ods` `.odp` |
| **PDF and e-books** | `.pdf` `.epub` |
| **Data** | `.csv` `.tsv` `.json` `.xml` `.yaml` `.toml` `.ini` `.sql` |
| **Code** | `.go` `.py` `.js` `.ts` `.java` `.cs` `.c` `.cpp` `.ps1` `.bat` `.sh` |
| **Web and text** | `.txt` `.log` `.md` `.html` `.css` `.conf` `.cfg` |
| **Mail and contacts** | `.eml` `.msg` `.vcf` |
| **Images (OCR)** | `.jpg` `.png` `.tif` `.bmp` `.gif` `.webp` |

## Download

Version 1.0.0 · One file: download and run. The index and settings stay on this computer only; uninstalling removes them all.

**Windows** — `digsearch-1.0.0.exe · ~59 MB`

- Windows 10 / 11, 64 bit
- Exe: no installer, no administrator rights; an MSI installer if you prefer
- PDF reading and OCR built in

[⤓ Download for Windows](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe) &nbsp;·&nbsp; [⤓ MSI](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msi)

**macOS** — `digsearch-1.0.0-macos-arm64.dmg · digsearch-1.0.0-macos-amd64.dmg`

- Apple Silicon (M1 and later) or Intel; open the DMG and drag the app to Applications
- Unsigned: if macOS says it cannot be opened, use System Settings › Privacy & Security › Open Anyway, or run `xattr -cr /Applications/DigSearch.app` in Terminal
- PDF reading and OCR built in
- For the Ctrl-Ctrl quick search macOS asks once for Accessibility permission

[⤓ Apple Silicon](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.dmg) &nbsp;·&nbsp; [⤓ Intel](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.dmg)

**Linux** — `digsearch-1.0.0-linux-amd64 · ~55 MB`

- x86-64, one file: download, `chmod +x digsearch-1.0.0-linux-amd64` and run it
- Chrome, Chromium, Edge or Brave for the window; otherwise your browser
- PDF reading and OCR built in
- The Ctrl-Ctrl quick search works in X11 sessions (not under Wayland)

[⤓ Linux amd64](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64)

---

DigSearch never connects to the internet, needs no account and sends nothing. PDF reading by MuPDF (AGPL), OCR by Tesseract.

© 2026 Mehmet Göğebakan
