# 🛠️ Nyx Toolkit

> **Client-Side Document Utilities | Zero-Server Architecture**

![License: MIT](https://img.shields.io/badge/License-MIT-gray)
![Platform: Web/Static](https://img.shields.io/badge/Architecture-Single--File-blue)
![Stack: HTML5/CSS3/JS](https://img.shields.io/badge/Stack-HTML5--CSS3--JS-orange)

## 📖 Overview

Nyx Toolkit is a collection of open-source document manipulation tools designed for privacy and portability. Conventional "free" online tools often require remote server uploads, imposing file-size caps and data privacy risks.

**Nyx Toolkit operates entirely within the browser.** By utilizing client-side processing, sensitive data never leaves the local environment.

> ### [Tryout now!](https://nyxtoolkit.web.app/)

---

## 🚀 Core Utilities

### 📄 PDF Splitter

- **Functionality:** Deconstructs large PDFs into user-defined segments.
- **Architecture:** Processes files locally via browser RAM.
- **Performance:** Supports ~220MB on mobile; 500MB+ on desktop (hardware dependent).
- **Selection:** Supports visual page selection and manual range inputs.

### 🔗 PDF Merger

- **Functionality:** Combines multiple PDF files into a single document.
- **Logic:** Drag-and-drop interface for defining merge sequence.
- **Processing:** Instant local execution; no upload latency.

### 🔄 File Converter

- **Supported Operations:**
  - `DOCX` ➔ `PDF`
  - `TXT` ➔ `PDF`
  - `IMG` ➔ `PDF`
  - `PDF` ➔ `PNG`
  - `PDF` ➔ `TXT`

### 📸 Long Screenshot Splitter

- **Functionality:** Segments vertical "scrolling" screenshots.
- **Optimization:** Splits images based on standard aspect ratios for easier viewing and printing.

### 📝 Markdown to PNG

- **Functionality:** Renders Markdown text as shareable PNG images.
- **Note:** Current build does not include code block syntax highlighting.

---

## 🗺️ Roadmap

- [ ] **Advanced OCR:** Enhanced text extraction for scanned documents.
- [ ] **Syntax Highlighting:** Integration for Markdown code blocks.
- [ ] **Extended Formats:** `CSV`, `JSON`, and `EPUB` support.

---

## ⚖️ License

Licensed under the **MIT License**.

---

_Developed by Knigh/Reish/Nyx (Solo-Dev Project)_
