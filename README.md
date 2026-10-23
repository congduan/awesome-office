# Awesome Office [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome open-source projects for office software: full office suites, document/spreadsheet/presentation SDKs, legacy Office 97-2003 format tools, converters, and AI-powered document intelligence. **Inclusion criterion: projects must read and/or write real office document formats (.docx, .xlsx, .pptx, .odt/.ods/.odp, legacy .doc/.xls, OLE2, PDF). Projects that only handle proprietary or plain-web formats are not included.**

In the AI era, more individuals and organizations are building their own office software. This list collects the best open-source building blocks — from the classic [LibreOffice](https://www.libreoffice.org/) and [ONLYOFFICE](https://github.com/ONLYOFFICE/DocumentServer) to modern AI-native suites and the libraries that read and write `.docx`, `.xlsx`, `.pptx`, and legacy binary formats.

> ⭐ Star counts are approximate, last verified in October 2026.

## Contents

- [Office Suites & Collaborative Workspaces](#office-suites--collaborative-workspaces)
- [Spreadsheets, Grids & Data Tables](#spreadsheets-grids--data-tables)
- [Document Format SDKs & Libraries](#document-format-sdks--libraries)
  - [.NET (incl. Open XML SDK)](#net-incl-open-xml-sdk)
  - [Java](#java)
  - [Python](#python)
  - [JavaScript / TypeScript](#javascript--typescript)
  - [Go / PHP / Rust](#go--php--rust)
- [Document Conversion & Processing](#document-conversion--processing)
- [PDF Tools & Libraries](#pdf-tools--libraries)
- [AI Document Intelligence](#ai-document-intelligence)
- [Legacy / Office 2003 Era Formats](#legacy--office-2003-era-formats)
- [AI Agent Skills & MCP Servers](#ai-agent-skills--mcp-servers)
- [Standards & Specifications](#standards--specifications)
- [Related Awesome Lists](#related-awesome-lists)

---

### Office Suites & Collaborative Workspaces

Full-blown office suites, online editors, and collaborative workspaces.

- [wordcraft](https://github.com/storytold/wordcraft) - An open-source, clean-room reimplementation of Microsoft Word in pure Rust `⭐ 15.6k`
- [genoffice](https://github.com/genspark-ai/genoffice) - Free, open-source AI Office suite: Docs, Sheets, Slides, PDF editors with a built-in AI agent `⭐ 10.5k`
- [cryptpad](https://github.com/cryptpad/cryptpad) - Collaborative office suite, end-to-end encrypted and open-source. `⭐ 8.0k`
- [DocumentServer](https://github.com/ONLYOFFICE/DocumentServer) - ONLYOFFICE Docs is a free collaborative online office suite comprising viewers and editors for texts, spreadsheets and presentations `⭐ 7.0k`
- [core](https://github.com/LibreOffice/core) - The LibreOffice core repository (development happens on Gerrit) `⭐ 4.6k`
- [online](https://github.com/CollaboraOnline/online) - Issue tracker only. Active development is on Gerrit at https://gerrit.collaboraoffice.com/. `⭐ 3.4k`
- [docx-editor](https://github.com/superdoc/docx-editor) - SuperDoc - Build AI agents that work with DOCX (DOCX Editor, DOCX Agent SDK) `⭐ 1.1k`
- [ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) - Ely Office: offline-first desktop apps in Rust and GPUI `⭐ 872`
- [edentext](https://github.com/stffnb/edentext) - Powerful web-based Word Processor for docx and odt.  Web-based word processor for docx and odt, private by design `⭐ 550`
- [richdocuments](https://github.com/nextcloud/richdocuments) - 📑 Collabora Online for Nextcloud `⭐ 459`
- [HermesOffice](https://github.com/criptogus/HermesOffice) - Free, open-source AI Office suite (Word, Excel, PowerPoint, PDF, Markdown) `⭐ 616`
- [jitword-sdk](https://github.com/jitOffice/jitword-sdk) - AI Word协同文档SDK，以文档编辑为核心，支持表格和思维导图协同编辑 `⭐ 219`
- [Apache OpenOffice](https://github.com/apache/openoffice) - The original open-source office suite, descendant of StarOffice (development on Apache) `⭐ 1.3k`
- [AbiWord](https://github.com/AbiWord/abiword) - Veteran lightweight word processor from GNOME's early days (official read-only mirror) `⭐ 178`
- [Gnumeric](https://github.com/GNOME/gnumeric) - The GNOME spreadsheet application, known for its calculation accuracy `⭐ 104`
- [Calligra](https://github.com/KDE/calligra) - Office and graphic art suite by KDE (successor of KOffice) `⭐ 210`


### Spreadsheets, Grids & Data Tables

Spreadsheet engines that read and write real Excel files.

- [univer](https://github.com/dream-num/univer) - The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one ru `⭐ 22.7k`
- [Luckysheet](https://github.com/dream-num/Luckysheet) - Luckysheet upgraded to Univer `⭐ 16.6k`
- [IronCalc](https://github.com/ironcalc/IronCalc) - Main engine of the IronCalc ecosystem `⭐ 4.2k`
- [Grist](https://github.com/gristlabs/grist-core) - Modern relational spreadsheet, the evolution of spreadsheets `⭐ 12.0k`



### .NET (incl. Open XML SDK)

Libraries for reading and writing Open XML (.docx/.xlsx/.pptx) files on .NET.

- [npoi](https://github.com/nissl-lab/npoi) - Read/write Office formats in .NET without Microsoft Office installed `⭐ 6.2k`
- [ClosedXML](https://github.com/ClosedXML/ClosedXML) - ClosedXML is a .NET library for reading, manipulating and writing Excel 2007+ (.xlsx, .xlsm) files. A friendly API over the OpenXML SDK. `⭐ 5.7k`
- [Open-XML-SDK](https://github.com/dotnet/Open-XML-SDK) - Open XML SDK by Microsoft `⭐ 4.6k`
- [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast library written in C# for reading Microsoft Excel files `⭐ 4.4k`
- [MiniExcel](https://github.com/mini-software/MiniExcel) - Lightweight, fast and native cross-platform processing tool for importing and exporting spreadsheet documents. `⭐ 3.7k`
- [EPPlus](https://github.com/EPPlusSoftware/EPPlus) - EPPlus-Excel spreadsheets for .NET `⭐ 2.0k`
- [openmcdf](https://github.com/openmcdf/openmcdf) - Microsoft Compound File Binary (COM Structured Storage) .NET Library `⭐ 392`

### Java

The Java ecosystem for Microsoft documents.

- [docx4j](https://github.com/plutext/docx4j) - JAXB-based Java library for Word docx, Powerpoint pptx, and Excel xlsx files `⭐ 2.4k`
- [poi](https://github.com/apache/poi) - Mirror of Apache POI gitbox. The Java API for Microsoft Documents. `⭐ 2.3k`
- [fastexcel](https://github.com/dhatim/fastexcel) - Generate and read big Excel files quickly `⭐ 912`

### Python

Python libraries for Office formats, including OLE2/Office 97-2003 parsing.

- [python-docx](https://github.com/python-openxml/python-docx) - Create and modify Word documents with Python `⭐ 5.7k`
- [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel XLSX files. `⭐ 4.0k`
- [python-pptx](https://github.com/scanny/python-pptx) - Create Open XML PowerPoint documents in Python `⭐ 3.6k`
- [python-docx-template](https://github.com/elapouya/python-docx-template) - Use a docx as a jinja2 template `⭐ 2.7k`
- [pyexcel](https://github.com/pyexcel/pyexcel) - One API for csv, ods, xls, xlsx and xlsm files `⭐ 1.3k`
- [olefile](https://github.com/decalage2/olefile) - Parse, read and write Microsoft OLE2 files (Structured Storage / Compound File Binary) `⭐ 274`
- [openpyxl](https://foss.heptapod.net/openpyxl/openpyxl) - A Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files (developed on GitLab/Heptapod)

### JavaScript / TypeScript

Generate, parse, and render Office documents in the browser or Node.js.

- [sheet.js](https://github.com/SheetJS/sheetjs) - SheetJS Spreadsheet Data Toolkit (moved to SheetJS/sheetjs) `⭐ 36.3k`
- [exceljs](https://github.com/exceljs/exceljs) - Excel Workbook Manager `⭐ 15.5k`
- [mammoth.js](https://github.com/mwilliamson/mammoth.js) - Convert Word documents (.docx files) to HTML `⭐ 6.3k`
- [PptxGenJS](https://github.com/gitbrent/PptxGenJS) - Build PowerPoint presentations with JavaScript. Works with Node, React, web browsers, and more. `⭐ 6.3k`
- [docx](https://github.com/dolanmiu/docx) - Easily generate and modify .docx files with JS/TS with a nice declarative API. Works for Node and on the Br `⭐ 6.0k`
- [docxtemplater](https://github.com/open-xml-templating/docxtemplater) - Generate docx/pptx/xlsx from templates in Node.js or the browser `⭐ 3.6k`
- [docxjs](https://github.com/VolodymyrBaydalka/docxjs) - Docx rendering library `⭐ 2.1k`

### Go / PHP / Rust

Office format libraries across Go, PHP, and Rust.

- [excelize](https://github.com/qax-os/excelize) - Go language library for reading and writing Microsoft Excel™ (XLAM / XLSM / XLSX / XLTM / XLTX) spreadsheets `⭐ 21.0k`
- [phpspreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files `⭐ 14.0k`
- [phpword](https://github.com/PHPOffice/PHPWord) - A pure PHP library for reading and writing word processing documents `⭐ 7.6k`
- [xlsx](https://github.com/tealeg/xlsx) - Go library for reading and writing XLSX files. `⭐ 6.0k`
- [calamine](https://github.com/tafia/calamine) - A pure Rust Excel/OpenDocument SpreadSheets file reader: rust on metal sheets `⭐ 2.5k`
- [phppresentation](https://github.com/PHPOffice/PHPPresentation) - A pure PHP library for reading and writing presentations documents `⭐ 1.4k`

### Document Conversion & Processing

Convert and process documents between formats.

- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - #1 PDF Application on GitHub that lets you edit PDFs on any device anywhere `⭐ 94.8k`
- [pandoc](https://github.com/jgm/pandoc) - Universal markup converter `⭐ 46.7k`
- [gotenberg](https://github.com/gotenberg/gotenberg) - A developer-friendly API for converting many document formats into PDF files, and more! `⭐ 13.4k`
- [textract](https://github.com/deanmalmgren/textract) - extract text from any document. no muss. no fuss. `⭐ 4.7k`
- [unoserver](https://github.com/unoconv/unoserver) - LibreOffice-based document conversion service (successor of unoconv) `⭐ 943`

### PDF Tools & Libraries

PDF viewers, parsers, and manipulators.

- [pdf.js](https://github.com/mozilla/pdf.js) - PDF Reader in JavaScript `⭐ 54.0k`
- [pdfplumber](https://github.com/jsvine/pdfplumber) - Extract text, tables and metadata from PDFs with detailed layout info `⭐ 10.8k`
- [pypdf](https://github.com/py-pdf/pypdf) - A pure-python PDF library capable of splitting, merging, cropping, and transforming the pages of PDF files `⭐ 10.3k`
- [pdfarranger](https://github.com/pdfarranger/pdfarranger) - GTK app to merge, split, rotate and crop PDF documents `⭐ 6.0k`
- [pdfbox](https://github.com/apache/pdfbox) - Mirror of Apache PDFBox `⭐ 3.1k`

### AI Document Intelligence

AI-era tools that turn office documents and PDFs into structured, LLM-ready data.

- [markitdown](https://github.com/microsoft/markitdown) - Python tool for converting files and office documents to Markdown. `⭐ 191.7k`
- [MinerU](https://github.com/opendatalab/MinerU) - Transforms PDFs and Office docs into LLM-ready markdown/JSON `⭐ 82.3k`
- [docling](https://github.com/docling-project/docling) - Get your documents ready for gen AI `⭐ 69.4k`
- [marker](https://github.com/datalab-to/marker) - Convert PDF to markdown + JSON quickly with high accuracy `⭐ 40.6k`
- [olmocr](https://github.com/allenai/olmocr) - Toolkit for linearizing PDFs for LLM datasets/training `⭐ 19.8k`
- [unstructured](https://github.com/Unstructured-IO/unstructured) - Open-source ETL for turning documents into structured data for LLMs `⭐ 15.6k`


## Legacy / Office 2003 Era Formats

Tools focused on the pre-OOXML binary formats (.doc, .xls, .ppt, OLE2 Compound File):

- [Apache POI](https://github.com/apache/poi) - The Java API for Microsoft Documents, including the HWPF/HSSF/XSSF families for 97-2003 binary formats `⭐ 2.3k`
- [olefile](https://github.com/decalage2/olefile) - Parse, read and write Microsoft OLE2 (Compound File Binary) files such as Office 97-2003 documents `⭐ 274`
- [openmcdf](https://github.com/ironfede/openmcdf) - Microsoft Compound File Binary (COM Structured Storage) .NET library `⭐ 392`
- [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight and fast C# reader for legacy .xls and .xlsx files `⭐ 4.4k`
- [xlrd](https://github.com/python-excel/xlrd) - Library for developers to extract data from legacy Excel .xls files `⭐ 2.2k`
- [jitOffice/doc2docx](https://github.com/jitOffice/doc2docx) - Convert Word 97-2003 binary .doc to OOXML .docx with zero host dependencies
- [catdoc](https://github.com/petewarden/catdoc) - Classic command-line converter for extracting text from MS Word .doc files `⭐ 89`
- [antiword](https://github.com/grobian/antiword) - Free MS Word 97-2003 .doc reader, a Unix classic since 1998 `⭐ 82`
- [libstaroffice](https://github.com/fosnola/libstaroffice) - Import filter for all StarOffice/LibreOffice legacy documents (the engine behind LibreOffice's .sdc/.sdd/.smf support)
- [wvWare](https://github.com/remram44/wvware) - Library for converting Word 97-2003 .doc to HTML (unofficial mirror of the SourceForge project)
- [OpenDocument.droid](https://github.com/opendocument-app/OpenDocument.droid) - Android's first OpenDocument / OpenOffice reader `⭐ 480`

## Standards & Specifications

Official specifications of the document formats that all these projects implement:

- [OOXML (ECMA-376 / ISO 29500)](https://ecma-international.org/publications-and-standards/standards/ecma-376/) - Office Open XML File Formats: the official spec behind .docx, .xlsx and .pptx (free download from ECMA)
- [ISO/IEC 29500 Transitional & Strict](https://www.iso.org/standard/71691.html) - The ISO edition of the OOXML standard
- [Open Document Format (ODF 1.3, ISO 26300)](https://docs.oasis-open.org/office/OpenDocument/v1.3/) - The OASIS standard for .odt/.ods/.odp documents
- [MS-OFFCRYPTO](https://learn.microsoft.com/en-us/openspecs/office_file_formats/ms-offcrypto/) - Microsoft's specification of Office binary file (transitional) encryption
- [MS-DOC / MS-XLS / MS-PPT](https://learn.microsoft.com/en-us/openspecs/office_file_formats/ms-doc/) - Microsoft's documented specifications of the legacy Word 97-2003 (.doc), Excel (.xls) and PowerPoint (.ppt) binary formats
- [Compound File Binary Format](https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-cfb/) - MS-CFB: the OLE2 / Structured Storage container used by all Office 97-2003 files
- [RTF Spec v1.9.1](https://www.microsoft.com/en-us/download/details.aspx?id=10725) - Rich Text Format specification
- [OOXML Documentation on learn.microsoft.com](https://learn.microsoft.com/en-us/dotnet/api/documentformat.openxml) - API reference for the Open XML SDK

## Related Awesome Lists

Other curated lists in nearby territory:

- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) - The mother of all awesome lists `⭐ 523.2k`
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - Self-hostable free software, including many office/collaboration tools `⭐ 329.4k`
- [awesome-document-understanding](https://github.com/tstanislawek/awesome-document-understanding) - Resources for Document Understanding and DocAI `⭐ 1.5k`
- [awesome-grid](https://github.com/FancyGrid/awesome-grid) - Curated list of grid/table libraries `⭐ 1.6k`

## AI Agent Skills & MCP Servers

Tools that let AI agents (Claude, ChatGPT, Codex, Cursor...) create and edit office documents.

### Agent Skills

Reusable skill packages that teach agents how to handle office document formats:

- [anthropics/skills](https://github.com/anthropics/skills) - Official Anthropic Agent Skills repo, including the `docx`, `pptx`, `xlsx` and `pdf` document skills `⭐ 183.1k`

### MCP Servers

Model Context Protocol servers for office document manipulation:

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) - Official MCP reference servers `⭐ 91.5k`
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - The curated list of MCP servers (see its Office/document section) `⭐ 96.8k`
- [excel-mcp-server (haris-musa)](https://github.com/haris-musa/excel-mcp-server) - Let AI agents create and edit Excel files with formulas, formatting and charts `⭐ 4.3k`
- [Office-Word-MCP-Server](https://github.com/GongRzhe/Office-Word-MCP-Server) - MCP server for creating, reading and manipulating Word documents `⭐ 2.1k`
- [Office-PowerPoint-MCP-Server](https://github.com/GongRzhe/Office-PowerPoint-MCP-Server) - MCP server for PowerPoint creation and manipulation `⭐ 1.9k`
- [excel-mcp-server (negokaz)](https://github.com/negokaz/excel-mcp-server) - MCP server that reads and writes MS Excel data with formula support `⭐ 1.0k`
- [MinerU-Document-Explorer](https://github.com/opendatalab/MinerU-Document-Explorer) - Agent-native knowledge engine with MCP tools for document indexing `⭐ 643`

### Agent-Native Document Tools

- [xberg](https://github.com/xberg-io/xberg) - Polyglot document intelligence with a Rust core: text/metadata extraction for agents `⭐ 9.4k`
- [kordoc](https://github.com/chrisryugj/kordoc) - Parse HWP/HWPX/PDF/Office documents to Markdown; CLI + MCP server `⭐ 2.7k`
- [anymd](https://github.com/SylphxAI/anymd) - Any file (PDF, Word, PowerPoint, Excel) to clean Markdown for AI agents `⭐ 1.1k`

## Contributing

Contributions are welcome! Please open a PR to add projects. Criteria:

1. Open source (permissive or copyleft license)
2. Actively maintained or historically significant
3. Must read and/or write real office document formats (Open XML, ODF, legacy binary, PDF) — grid/widget-only projects without office format I/O are out of scope

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
