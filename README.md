# 📄 Summarize PDF with ChatGPT

This project allows you to **automatically generate summaries from PDF documents** using the power of **OpenAI's ChatGPT API**. It simplifies document review, research analysis, and reading large reports—saving you hours of manual reading.

> ⚠️ This tool uses the **ChatGPT API**, which requires a valid OpenAI API key and incurs usage costs. Refer to [OpenAI pricing](https://openai.com/pricing) for more details.

---

## 🚀 Features

* 🔍 Extract text from PDF files
* 💬 Summarize with OpenAI GPT models (e.g., `gpt-3.5-turbo`)
* 📊 Choose chunk sizes and summarization styles
* 🧪 Jupyter Notebook implementation for flexibility and experimentation
* ☁️ Run locally or on Google Colab (no installation required)

---

## 📦 Project Structure

```
Summarize-PDF-ChatGPT/
├── LICENSE
├── README.md
├── Project/
│   ├── requirements.txt         # Python dependencies
│   └── summarize-chatgpt.ipynb  # Main notebook for summarization
```

---

## ⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Required libraries include:

* `openai`
* `PyMuPDF` (for PDF parsing)
* `tiktoken`
* `python-dotenv`
* `ipython`
* `ipywidgets`

---

## ☁️ Run on Google Colab (Recommended)

No setup needed! Just click the badge below to start instantly on Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/2black0/Summarize-with-ChatGPT/blob/main/summarize-chatgpt.ipynb)

---

## 💻 Run on Local Machine

1. **Create a virtual environment (optional but recommended):**

```bash
conda create -n openai python=3.9
conda activate openai
```

2. **Clone this repository:**

```bash
git clone https://github.com/2black0/Summarize-with-ChatGPT.git
cd Summarize-with-ChatGPT
```

3. **Install requirements:**

```bash
pip install -r Project/requirements.txt
```

4. **Launch Jupyter:**

```bash
jupyter lab
```

---

## 🔑 API Configuration

Make sure you have your OpenAI API Key ready. You can add it to your environment or load it from a `.env` file:

```env
OPENAI_API_KEY=your_api_key_here
```

You can also manually paste the API key inside the notebook input if prompted.

---

## 📝 How It Works

1. Upload a PDF document.
2. The notebook extracts text and splits it into manageable chunks.
3. Each chunk is summarized using ChatGPT via API.
4. Final output is a full summary of the original PDF.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---