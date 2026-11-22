# OmniDoc

OmniDoc is a free-to-use office suite for Windows, macOS and Linux. It edits documents, spreadsheets, presentations and PDFs on your own computer, and it also offers free whole-document translation and free structured extraction in the browser.

[Website](https://omnidoc.top/) · [Download](https://download.omnidoc.top/) · [Developer documentation](https://docs.omnidoc.top/) · [MCP server](https://github.com/lamg-Chen/omnidoc-mcp) · [中文](#omnidoc-中文)

![The UniDoc editor in OmniDoc with an interactive sample document: a temperature slider drives the Planck curve, the peak marker and the numbers in the text](https://omnidoc.top/images/screenshots/en/unidoc-interactive-v2-1280.webp)

## Download

The current release is **OmniDoc 1.20**: build 144 for Windows 10 and 11 (x64), build 133 for macOS 12 or later (Intel) and for 64-bit Debian-based Linux such as Ubuntu 20.04 and Debian 11. Get the installers from the [download page](https://download.omnidoc.top/).

## What you can edit

- **Documents:** text, headings, styles, tables, equations and page layout. Word files open and save as standard .docx.
- **Spreadsheets:** several sheets, formulas, conditional formatting, charts and sparklines. Excel files open and save as standard .xlsx.
- **Presentations:** slide content, tables, charts and speaker notes, saved as standard .pptx.
- **PDF:** click into a paragraph and type; the layout you see while typing is the layout that is saved. Signatures, forms, text recognition and export to Word, Excel and PowerPoint are included.

![A two-column paper in the UniDoc editor with numbered equations, a vector sketch and a framed result box](https://omnidoc.top/images/screenshots/en/unidoc-paper-v2-1280.webp)

![A workbook in UniCell: each cell is calculated with Planck's formula and coloured with a colour scale, the formula bar shows the formula of cell D16, and a chart shows four curves](https://omnidoc.top/images/screenshots/en/unicell-v2-1280.webp)

## Speed and file formats

- A 13.6 MB research paper in PDF shows its first page about 4 seconds after launch and saves in about 0.06 seconds. Writing a typed PDF paragraph back takes about 0.3 seconds.
- In the document editor a key press is laid out in about 9 milliseconds, also in documents of more than 10,000 pages.
- Word content controls, bookmarks, page breaks, headers, footers and footnotes are kept. Excel formulas, native charts, pivot tables, conditional formatting, filters and sparklines keep working.
- OFD files (GB/T 33190) open, edit and convert to and from PDF. Templates follow GB/T 7714—2015 references and the GB/T 7713.1 thesis layout.

## AI assistants (MCP)

The desktop app includes an MCP server with more than 40 document tools. Claude, Codex, Cursor and other MCP clients can create, read, edit and export Word, Excel, PowerPoint and PDF files on your computer, and a document that is open in OmniDoc updates in place while the assistant works. Editing and conversion run offline; cloud services such as paid translation use credits. No API key is needed. See [omnidoc-mcp](https://github.com/lamg-Chen/omnidoc-mcp) and the [developer documentation](https://docs.omnidoc.top/).

## Free document translation

Open [translate.omnidoc.top](https://translate.omnidoc.top/en/) and sign in with an OmniDoc account (registration is free). Upload a whole PDF, Word or PowerPoint file and download the translation when it is done. Headings, paragraphs, tables, formulas and pictures stay in place, and PDFs come back as a bilingual version and a translation-only version.

- Up to 2,000 pages per PDF, no monthly cap.
- Free jobs wait in a queue. The desktop app has no page limit and no queue.
- More than 30 target languages, including English, Chinese, Spanish, French, German, Japanese, Korean, Russian and Arabic.
- It is machine translation: check figures, terms and citations in important files.

![A physics note translated into a bilingual document: each paragraph shows the original followed by the translation, and the numbered equation stays in place](https://omnidoc.top/images/screenshots/en/translate-bilingual-v2-1280.webp)

## Free structured extraction

Open [extract.omnidoc.top](https://extract.omnidoc.top/en/), sign in and upload a PDF, a scan, or a Word, PowerPoint or Excel file. You get a ZIP with `document.md` (Markdown), `document.json` (structured data in reading order), `images/` and `manifest.json`. Heading levels, paragraphs and table rows and columns are kept. Up to 501 pages per PDF; free jobs wait in a queue. Check text recognition results against the original, especially numbers and tables.

## Not to be confused with

Several unrelated projects share the name. This repository is OmniDoc (至译) of [omnidoc.top](https://omnidoc.top/) and [omnidoc.cn](https://omnidoc.cn/), not:

- **OmniDocBench** ([opendatalab/OmniDocBench](https://github.com/opendatalab/OmniDocBench)): a benchmark for document parsing models (CVPR 2025), not a product. Scores "on OmniDocBench" refer to that benchmark.
- **Omnidoc** ([omnidoc.fr](https://omnidoc.fr/)): a French medical tele-expertise platform.
- **Omnidocs** ([omnidocs.com](https://omnidocs.com/)): document and template management for Microsoft 365.
- **omniDOC** by Thistle Scientific: a laboratory gel documentation system.
- The `omnidoc` Go package and an OmniDoc documentation tool for JavaScript/TypeScript code.

Full table with sources: [Which OmniDoc is which](https://omnidoc.top/guides/what-is-omnidoc/en/).

## License

OmniDoc is proprietary software, not open source. It can be downloaded, installed and used free of charge; this repository holds documentation only. Online features (accounts, translation, AI, sharing and signing) are governed by the [Terms of Service](https://omnidoc.top/terms) and [Privacy Policy](https://omnidoc.top/privacy).

---

# OmniDoc 中文

OmniDoc 是可以免费下载使用的办公软件，支持 Windows、macOS 和 Linux：在自己的电脑上编辑文档、表格、演示文稿和 PDF；浏览器里还有免费整篇文档翻译和免费结构化提取。

[官网](https://omnidoc.top/) · [下载](https://download.omnidoc.top/) · [开发者文档](https://docs.omnidoc.top/) · [MCP 服务](https://github.com/lamg-Chen/omnidoc-mcp)

![UniDoc 编辑器中的互动示例文档：拖动温度滑块，普朗克曲线、峰值标记和正文里的数字一起变化](https://omnidoc.top/images/screenshots/zh/unidoc-interactive-v2-1280.webp)

## 下载

当前版本 **OmniDoc 1.20**：Windows 10 / 11（64 位）为 build 144，macOS 12 及以上（Intel）和 64 位 Debian 系 Linux（如 Ubuntu 20.04、Debian 11）为 build 133。安装包在[下载页](https://download.omnidoc.top/)。

## 能编辑什么

- **文档**：正文、标题、样式、表格、公式和页面排版，Word 文件直接打开、存回标准 .docx。
- **表格**：多张工作表、公式、条件格式、图表和迷你图，存回标准 .xlsx。
- **演示文稿**：幻灯片内容、表格、图表和备注，存回标准 .pptx。
- **PDF**：点进段落直接改字，打字时看到的就是保存后的排版；另有电子签名、表单、文字识别，以及导出 Word、Excel、PowerPoint。

![UniDoc 编辑器中的双栏论文：编号公式、矢量示意图和带边框的结论框](https://omnidoc.top/images/screenshots/zh/unidoc-paper-v2-1280.webp)

![UniCell 中的工作簿：每格按普朗克公式计算并按色阶着色，编辑栏显示 D16 的公式，图表画出四条曲线](https://omnidoc.top/images/screenshots/zh/unicell-v2-1280.webp)

## 速度与格式

- 13.6 MB 的论文 PDF 从启动到显示第一页约 4 秒，保存约 0.06 秒；PDF 段落里打的字写回约 0.3 秒。
- 文档编辑器从按键到排好版约 9 毫秒，一万多页的文档也一样。
- Word 的内容控件、书签、分页符、页眉页脚和脚注原样保留；Excel 的公式、原生图表、数据透视表、条件格式、筛选和迷你图照常工作。
- OFD 版式文件（GB/T 33190）可以打开、编辑，并与 PDF 互转；模板按 GB/T 7714—2015 著录参考文献，学位论文按 GB/T 7713.1 排版。

## AI 助手（MCP）

桌面版自带 MCP 服务，40 多个文档工具。Claude、Codex、Cursor 等 MCP 客户端可以在你的电脑上新建、读取、修改和导出 Word、Excel、PowerPoint 和 PDF；在 OmniDoc 里打开着的文档会跟着 AI 的修改原地更新。编辑和格式转换离线进行；付费翻译等云端服务按积分计费，不需要 API Key。见 [omnidoc-mcp](https://github.com/lamg-Chen/omnidoc-mcp) 和[开发者文档](https://docs.omnidoc.top/)。

## 免费文档翻译

打开 [translate.omnidoc.top](https://translate.omnidoc.top/)，用 OmniDoc 账号登录（注册免费），上传整篇 PDF、Word 或 PowerPoint，处理完成后下载。标题、段落、表格、公式和图片留在原位，PDF 同时给双语对照版和纯译文版。

- 单个 PDF 最多 2000 页，不限每月次数。
- 免费任务按提交顺序排队；桌面版不限页数、不排队。
- 可译为英文、中文、西班牙文、法文、德文、日文、韩文、俄文、阿拉伯文等 30 多种语言。
- 免费翻译是机器翻译，重要文件请核对数字、术语和引用。

![一篇物理讲义译成双语文档：每段原文后面跟着译文，编号公式留在原位](https://omnidoc.top/images/screenshots/zh/translate-bilingual-v2-1280.webp)

## 免费结构化提取

打开 [extract.omnidoc.top](https://extract.omnidoc.top/)，登录后上传 PDF、扫描件、Word、PowerPoint 或 Excel，下载的 ZIP 里有 `document.md`（Markdown）、`document.json`（按阅读顺序的结构化数据）、`images/` 和 `manifest.json`。标题层级、段落和表格行列都会保留。单个 PDF 最多 501 页，免费任务排队处理。扫描件的识别结果请与原文核对，尤其是数字和表格。

## 同名区分

好几个无关的项目都叫这个名字。本仓库是 [omnidoc.top](https://omnidoc.top/) 和 [omnidoc.cn](https://omnidoc.cn/) 的 OmniDoc（至译），不是：

- **OmniDocBench**（[opendatalab/OmniDocBench](https://github.com/opendatalab/OmniDocBench)）：文档解析模型的评测基准（CVPR 2025），不是软件产品。「在 OmniDocBench 上得分多少」说的是它。
- **Omnidoc**（[omnidoc.fr](https://omnidoc.fr/)）：法国的医疗远程会诊平台。
- **Omnidocs**（[omnidocs.com](https://omnidocs.com/)）：Microsoft 365 里的文档与模板管理工具。
- Thistle Scientific 的 **omniDOC**：实验室凝胶成像系统。
- 名为 `omnidoc` 的 Go 语言库，以及一个给 JavaScript/TypeScript 代码写文档的 OmniDoc 工具。

完整对照表和出处：[OmniDoc 至译和同名产品怎么区分](https://omnidoc.cn/guides/what-is-omnidoc/)。

## 许可

OmniDoc 是专有软件，不开源；可以免费下载、安装和使用。本仓库只有说明文档。在线功能（账号、翻译、AI、分享、签署）另受[服务条款](https://omnidoc.top/terms)和[隐私政策](https://omnidoc.top/privacy)约束。
