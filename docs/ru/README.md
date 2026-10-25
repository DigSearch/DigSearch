<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@f3c4419caf21/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@f3c4419caf21/assets/wordmark-light.png" width="300" alt="DigSearch"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a> &nbsp;·&nbsp; <b>Русский</b></p>

<p align="center">Excel, Word, PowerPoint, PDF, сканы и текстовые файлы: каждая строка в тысячах файлов находится, пока вы печатаете. Работает полностью на вашем компьютере.</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@f3c4419caf21/assets/screens/ru/search.svg" width="840" alt="Поиск внутри файлов"></p>

<p align="center">✓ Один файл, без установки &nbsp;·&nbsp; ✓ Без интернета, данные у вас &nbsp;·&nbsp; ✓ Windows · Linux · macOS</p>

<p align="center"><a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe"><b>Windows</b></a> <sub>.exe</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64.tar.gz"><b>Linux</b></a> <sub>amd64</sub> &nbsp;|&nbsp; <a href="https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-arm64.tar.gz"><b>Linux</b></a> <sub>arm64</sub></p>

| **2 500** | **14 с** | **4–50 мс** | **30+** | **5** |
|:---:|:---:|:---:|:---:|:---:|
| файлов, 2,6 млн строк | первый индекс | выборочный поиск | типов файлов | языков: TR · EN · DE · 中文 · RU |

## Как это работает

1. **Добавьте папку** — При выборе папки рисуется карта ещё до чтения: сколько занимает каждая подпапка, какие там типы. Галочками выбираете, что искать.
2. **Строится индекс** — Файлы читаются всеми ядрами, текст пишется в сжатый индекс на диске. 2 500 файлов и 2,6 млн строк — около 14 секунд.
3. **Ищите, пока печатаете** — Результаты обновляются при каждом нажатии, с числом строк, файлов и типов. Выбранная строка открывается в предпросмотре.

### Каждая буква сужает поиск

![Каждая буква сужает поиск](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@f3c4419caf21/assets/screens/ru/typing.svg)

_Число совпадений сужается по мере ввода: каждая буква отсекает блоки-кандидаты._

## Возможности

### Поиск внутри файлов

Ячейки Excel, абзацы и таблицы Word, слайды PowerPoint, страницы PDF, текст и код. Несколько слов находят строки со всеми; "точная фраза" в кавычках.

> стойка 3 → **Стойка 3** серверная · 12 серверов

### OCR для сканов

Читаются страницы PDF без текстового слоя и изображения (JPG, PNG, TIFF). Прочитанные страницы сохраняются.

### Поиск по именам файлов и папок

Одна кнопка — поиск только по именам: хватит и одной буквы. * заменяет один символ. Папки тоже в списке, с датами.

> отчёт_202* → отчёт_202**5**.xlsx · отчёт_202**6**.docx

![Поиск по именам файлов и папок](https://cdn.jsdelivr.net/gh/DigSearch/DigSearch@f3c4419caf21/assets/screens/ru/names.svg)

### Мягко по умолчанию, точно по желанию

По умолчанию регистр и диакритика не важны. Aa — с учётом регистра, ab — только целые слова, .* — регулярные выражения. Живой поиск можно заменить на Enter.

### Иерархия или список — ваша таблица

Результаты группируются по файлам или каждое совпадение — строка. Выбирайте столбцы, переставляйте, меняйте ширину, подгоняйте двойным щелчком. Фильтр содержит / не содержит по столбцам.

### Экспорт в Excel или CSV

Показанные столбцы и отфильтрованные строки, одно совпадение — строка: xlsx (жирный заголовок, закреплённая строка) или UTF-8 CSV через системный диалог.

### Предпросмотр на месте

Выбранный файл открывается справа и прокручивается к совпадению; при прокрутке подгружается дальше. Листы Excel — вкладками, таблицы — с заголовками. Поиск в файле, копирование строки или таблицы, открытие в редакторе.

### Анализ папки

Масштабируемая карта размеров, дубликаты, большие и старые файлы, карта размер × возраст. Отмеченное — в корзину.

### Изменения сами собой

В отслеживаемой папке добавленные, изменённые и удалённые файлы попадают в индекс за секунды. Остальные папки сканируются при запуске и по запросу.

### Миллисекунды на миллионах строк

Текст хранится в индексе из блоков; поиск читает только блоки-кандидаты. Выборочный поиск по 2,6 млн строк — 4–50 мс. Память и процессор подстраиваются под машину.

### Всё на вашем компьютере

Без интернета и аккаунта, ничего не отправляется. Индекс и настройки в локальной папке, удаляются вместе с программой.

### Пять языков, с клавиатуры

Türkçe, English, Deutsch, 中文, Русский. / — в строку поиска, ↑↓ — по совпадениям, Ctrl+K — анализ, Ctrl+Enter — открыть файл.

## Читаемые типы файлов

Можно добавить свои расширения; они читаются построчно как текст. Ненужные типы отключаются по папкам.

| | |
|---|---|
| **Офис** | `.xlsx` `.xlsm` `.docx` `.docm` `.pptx` `.rtf` `.odt` `.ods` `.odp` |
| **PDF и электронные книги** | `.pdf` `.epub` |
| **Данные** | `.csv` `.tsv` `.json` `.xml` `.yaml` `.toml` `.ini` `.sql` |
| **Код** | `.go` `.py` `.js` `.ts` `.java` `.cs` `.c` `.cpp` `.ps1` `.bat` `.sh` |
| **Веб и текст** | `.txt` `.log` `.md` `.html` `.css` `.conf` `.cfg` |
| **Почта и контакты** | `.eml` `.msg` `.vcf` |
| **Изображения (OCR)** | `.jpg` `.png` `.tif` `.bmp` `.gif` `.webp` |

## Скачать

Версия 1.0.0 · Один файл: скачайте и запустите. Индекс и настройки хранятся только на этом компьютере; при удалении всё стирается.

**Windows** — `digsearch-1.0.0.exe · ~59 MB`

- Windows 10 / 11, 64 бит
- Exe: без установки и прав администратора; по желанию установщик MSI или пакет MSIX
- Чтение PDF и OCR встроены

[⤓ Скачать для Windows](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0.exe) &nbsp;·&nbsp; [⤓ MSI](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msi) &nbsp;·&nbsp; [⤓ MSIX](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-x64.msix)

**macOS** — `digsearch-1.0.0-macos-arm64.zip · digsearch-1.0.0-macos-amd64.zip`

- Apple Silicon (M1 и новее) или Intel
- Без подписи: при первом запуске правый клик › Открыть
- Использует mutool для PDF и tesseract для OCR, если установлены

[⤓ Apple Silicon](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-macos-amd64.zip)

**Linux** — `digsearch-1.0.0-linux-amd64.tar.gz · digsearch-1.0.0-linux-arm64.tar.gz`

- x86-64 или arm64, один бинарник; kur.sh добавит в меню
- Окно через Chrome, Chromium, Edge или Brave; иначе в браузере
- Использует mutool для PDF и tesseract для OCR, если установлены

[⤓ Linux amd64](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-amd64.tar.gz) &nbsp;·&nbsp; [⤓ Linux arm64](https://github.com/DigSearch/DigSearch/releases/download/v1.0.0/digsearch-1.0.0-linux-arm64.tar.gz)

---

DigSearch не выходит в интернет, не требует аккаунта и ничего не отправляет. Чтение PDF — MuPDF (AGPL), OCR — Tesseract.

© 2026 Mehmet Göğebakan
