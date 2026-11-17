# OCR Local Neural Engine

[![Release](https://img.shields.io/badge/release-v1.0.0-blue.svg?style=flat-square)](https://github.com/vishwasupponi/vtx-ocr-engine/releases)
[![Category](https://img.shields.io/badge/category-Core%20Engines-orange.svg?style=flat-square)](#)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-red.svg?style=flat-square)](LICENSE)

OCR Local Neural Engine is an official core engine module for the **Vertex Application**. It provides local, deep-learning optical character recognition to digitize scanned document images and non-vector PDF bank statements without sending files to external cloud vision APIs. Built as an offline neural backbone, it seamlessly powers text and tabular extraction for interactive tools across the Vertex ecosystem.

> [!NOTE]
> **Internet Usage**: 100% offline. Neural OCR processing runs locally on your computer and does not use an internet connection.

---

## ✨ Key Features

- **🧠 100% Offline Neural OCR**: Executes deep-learning computer vision models entirely on local CPU silicon with zero cloud API dependencies.
- **⚡ Hardware-Optimized Inference**: Utilizes optimized mathematical kernels for fast, multi-threaded inference on modern x86-64 processors.
- **🧩 Headless Core Service Architecture**: Designed as a shared computational dependency that can be summoned dynamically by any Vertex module.
- **🔒 Zero Data Exposure**: Client documents and sensitive financial imagery are processed strictly in volatile memory and never transmitted remotely.

---

## 📥 Installation

### Via Vertex Module Manager (Recommended)
1. Open the **Vertex Application**.
2. Go to **Settings** in the sidebar and then **Module Manager**.
3. Switch to the **Cloud Store** tab, locate **OCR Local Neural Engine**, and click **Install**.
4. The engine will install silently and be automatically utilized by modules (such as Bank Statement Converter) when processing scanned documents.

### Manual Package Installation
1. Download the latest release `.vtx` package from the [Releases](https://github.com/vishwasupponi/vtx-ocr-engine/releases) page.
2. In Vertex Module Manager, click **"Install Local File"** and choose the downloaded package.

---

## 🚀 Getting Started

1. **Automatic Integration**: As a core background engine, this module requires no standalone manual launcher.
2. **Enable Scanned Processing**: Open **Bank Statement Converter** (or any OCR-dependent module) in Vertex.
3. **Run**: When you select scanned statement PDFs or table images, the OCR Local Neural Engine is automatically invoked in the background for local character recognition.

> For more information, check the **Instructions** manual inside Vertex.

---

## 🤝 Contributing & Security

- You are free to develop custom plugins for personal use. To propose a module for the official Cloud Store catalog or submit contributions, see [CONTRIBUTING.md](CONTRIBUTING.md).
- To report a security concern or review the security policy, see [SECURITY.md](SECURITY.md).

---

## 🙏 Acknowledgments

This module is built using various open-source libraries and components under their respective open-source licenses. Building this module would not have been possible without these foundational open-source technologies, and I thank all the original developers and maintainers of these projects for their contributions:

- **[PyTorch (torch)](https://pytorch.org/)** – Deep learning neural tensor compute engine for local visual inference.
- **[pytesseract](https://github.com/madmaze/pytesseract)** / **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)** – Optical character recognition engine for scanned document parsing.
- **[Pillow (PIL)](https://python-pillow.org/)** – Image pre-processing, grayscale thresholding, and tensor conversions.

---

## 📄 License

This project is licensed under the [GNU Affero General Public License v3 (AGPL-3.0)](LICENSE).

Developed by [Vishwas Upponi](https://vishwasupponi.blogspot.com/links).
