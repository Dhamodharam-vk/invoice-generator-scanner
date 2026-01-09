# AI OCR & Workflow Automation

This project leverages **EasyOCR** for text extraction from images and integrates with **Euriai LangGraph** to handle complex, stateful AI workflows. It is designed to process images, extract textual data, and manage data flow using graph-based logic.

## 🚀 Features
* **Optical Character Recognition (OCR):** Powered by `easyocr` for high-accuracy text detection.
* **Image Processing:** Uses `PIL` (Pillow) for image manipulation, drawing bounding boxes, and preprocessing.
* **Stateful AI Logic:** Implements `EuriaiLangGraph` to manage the sequence of AI tasks.
* **Data Storage:** Uses `sqlite3` for local caching and data persistence.

## 🛠️ Tech Stack
* **Language:** Python
* **OCR:** [EasyOCR](https://github.com/JaidedAI/EasyOCR)
* **Image Lib:** Pillow (PIL)
* **Workflow:** Euriai LangGraph
* **Database:** SQLite

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
