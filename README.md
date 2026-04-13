# 🤖 AI Agent Using LangChain (Groq + Tools)

An intelligent **AI Agent project** built using **LangChain**, **Groq LLM**, and external tools like **DuckDuckGo Search** and **Weather API**.  
The agent can reason, use tools, search live information, and provide accurate responses dynamically.

---

## 🚀 Key Features

1. 🔍 **Web Search Tool**  
   Uses DuckDuckGo Search to fetch real-time information from the internet.

2. 🌦 **Weather Tool Integration**  
   Fetches live weather details of any city using WeatherStack API.

3. 🧠 **Reasoning AI Agent**  
   Uses LangChain Agent to think step-by-step before answering.

4. ⚡ **Powered by Groq LLM**  
   Fast and efficient responses using Llama models via Groq API.

5. 🛠 **Custom Tools Support**  
   Easily extendable with new tools like calculator, maps, stock data, etc.

6. 💬 **Natural Language Queries**  
   Ask in normal English and get smart answers.

---

## 📁 Project Structure

```bash
AI-Agent-Using-LangChain/
│── agent.ipynb
│── requirements.txt
│── README.md
```

---

## ⚙️ Tech Stack
| Layer      | Technology                     |
|------------|--------------------------------|
| Language	| Python |
| Framework	| LangChain |
| LLM Provider |	Groq API |
| Model |	Llama 3.1 / 3.3 |
| Search Tool |	DuckDuckGo |
| Weather API |	WeatherStack |
| Environment |	Jupyter Notebook / VS Code |

---


## 🛠 Setup Instructions

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Agent-Using-LangChain.git
cd AI-Agent-Using-LangChain
```

### Install Requirements

```bash
pip install -r requirements.txt
```

---

## 🔑 API Setup

### Create environment variables:

```bash
GROQ_API_KEY=your_groq_api_key
WEATHERSTACK_API_KEY=your_weatherstack_key
```

or inside notebook:

```bash
import os
os.environ["GROQ_API_KEY"] = "your_key"
```

---

## 📌 Future Improvements

- Add Stock Market Tool
- Add News Tool
- Add Currency Converter
- Add Streamlit Web UI
- Add Memory Chatbot Support

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
