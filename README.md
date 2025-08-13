# 🧠 AI Life Admin – Freedom from Mundane

**AI Life Admin** is a smart assistant that frees you from repetitive, boring tasks by turning messy, unstructured information into clear, actionable insights.  
It can take **images or text**, extract the content using OCR, and use AI to produce a **summary, action items, deadlines, and key people/organizations** — all from a simple, beautiful Gradio interface.

---

## 🚀 Features
- 📄 **Image to Text (OCR)** – Upload an image (JPEG, PNG) and extract text using `pytesseract`.
- ✍️ **Text Input** – Paste or type raw text directly into the app.
- 🤖 **AI Insights** – Uses an LLM (like GPT-4 or GPT-3.5) to:
  - Summarize content.
  - Extract action items.
  - Identify deadlines.
  - Detect people/organizations.
- 🎨 **Clean Gradio UI** – Minimal, interactive, and responsive.
- ⚡ **Fast & Simple** – Works locally or in the cloud.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- [Gradio](https://gradio.app/) – UI framework
- [pytesseract](https://pypi.org/project/pytesseract/) – OCR engine
- [Pillow](https://pypi.org/project/Pillow/) – Image processing
- [OpenAI API](https://platform.openai.com/) – LLM processing

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ai-life-admin.git
   cd ai-life-admin


python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

