# DeepDive 🔍

Minimal Multi-Agent AI Research System

DeepDive is a clean, minimal AI research assistant powered by a multi-agent pipeline. It autonomously searches the web, extracts relevant information, generates a structured report, and critiques its own output — all through a simple and elegant interface.

---

## ✨ Features

* 🔎 **Search Agent**
  Finds relevant and recent information

* 📄 **Reader Agent**
  Extracts and summarizes key content from sources

* ✍️ **Writer Agent**
  Generates a structured research report

* 🧐 **Critic Agent**
  Evaluates and improves the report quality

* 🎨 **Minimal UI**
  Clean black & white interface with subtle animations

---

## 🧠 Architecture

```
User Input
    ↓
Search Agent
    ↓
Reader Agent
    ↓
Writer Chain
    ↓
Critic Chain
    ↓
Final Report + Feedback
```

---

## 🖥️ UI Philosophy

* Minimal (black/white/gray only)
* No unnecessary animations
* Focused on readability and flow
* Inspired by tools like Notion, ChatGPT, and Linear

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/deepdive.git
cd deepdive
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add environment variables

Create a `.env` file:

```
OPENAI_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 📦 Tech Stack

* **Frontend**: Streamlit
* **LLM Orchestration**: LangChain
* **Search API**: Tavily
* **Language Model**: OpenAI GPT

---

## 📊 Example Use Cases

* Research papers
* Tech trend analysis
* AI/ML topic exploration
* Academic summaries
* Quick literature reviews

---

## ⚡ Future Improvements

* Streaming responses (ChatGPT-style)
* Source citation UI
* Agent reasoning logs
* Export to PDF / DOCX
* Real-time metrics (time, tokens, sources)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## 📜 License

MIT License

---

## 🙌 Acknowledgements

Inspired by modern AI tools and multi-agent systems.

---

## 💡 Author

Built by Abhijeet Kaja
Exploring AI, ML, and intelligent systems.
