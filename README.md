# UdaPlay-AI-Agent

# 🎮 UdaPlay AI Agent

## 📌 Overview

UdaPlay is an AI-powered research agent designed to answer natural language questions about video games using a hybrid retrieval system.

## ⚙️ Features

* 🔍 RAG-based retrieval using ChromaDB
* 🌐 Web fallback using Tavily API
* 🧠 Confidence-based evaluation system
* 🔄 Stateful agent workflow
* 📊 Structured output responses

## 🧱 Architecture

1. User Query
2. Vector DB Retrieval
3. Evaluation
4. Fallback to Web (if needed)
5. Final Answer Generation

## 🛠️ Tech Stack

* Python
* ChromaDB
* OpenAI API
* Tavily API

## ▶️ How to Run

1. Clone the repo:

```
git clone https://github.com/yourusername/UdaPlay-AI-Agent.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Create `.env` file:

```
OPENAI_API_KEY=your_key
TAVILY_API_KEY=your_key
```

4. Run notebooks:

* Udaplay_01_solution_project.ipynb
* Udaplay_02_solution_project.ipynb

## 🧪 Example Queries

* Who developed FIFA 21?
* When was God of War Ragnarok released?
* What platform was Pokemon Red launched on?

## 📚 Output

* Structured answers
* Source attribution (Local / Web)
* Confidence score
