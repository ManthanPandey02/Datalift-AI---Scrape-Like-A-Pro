# 🚀 Datalift AI – Scrape Like a Pro

**Datalift AI** is an AI-powered, prompt-driven web scraping application that extracts meaningful data from any public website using **open-source large language models (LLMs)** running locally. Built with Python, it combines the power of **Selenium**, **BeautifulSoup**, **Streamlit**, and **LangChain + Ollama** to deliver flexible, context-aware, and cost-effective scraping—no APIs required.

---

## 📌 Features

- ✅ **Simple UI** with Streamlit – No coding required  
- 🌐 **Scrape Any Public URL** – Supports dynamic websites  
- 🧹 **Cleans DOM** with BeautifulSoup – Removes noise like scripts/styles  
- 🧠 **LLM-Powered Parsing** – Understands natural language prompts  
- 🛡️ **Bypass Captchas** – Optional integration with Bright Data Scraping Browser  
- 📊 **Dynamic Output** – Summaries, tables, lists, and more based on prompt  
- ⚙️ **Modular Architecture** – Easily extend, debug, and enhance  

---

## 🧠 How It Works

1. **User Input:** Streamlit captures a website URL and natural prompt  
2. **Scraper:** Selenium or Bright Data loads and renders page  
3. **Cleaner:** BeautifulSoup removes unwanted tags from HTML  
4. **Splitter:** Content is chunked to fit LLM token limits  
5. **Parser:** LangChain + Ollama processes the chunks via LLaMA 3.1  
6. **Output:** Final structured result (text, table, summary, etc.)

---

## 🧰 Tech Stack

- **Frontend:** Streamlit  
- **Scraping:** Selenium, optionally Bright Data’s cloud browser  
- **Parsing:** LangChain + Ollama (LLaMA 3.1)  
- **Cleaning:** BeautifulSoup  
- **Language:** Python 3.10+

---

## 💻 Installation

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/datalift-ai.git
cd datalift-ai
