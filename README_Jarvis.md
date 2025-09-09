# Jarvis AI Assistant 🤖

Jarvis is a simple chatbot powered by OpenAI’s GPT models. It maintains conversation history and responds to user queries in a conversational style.

---

## 🚀 Features
- Interactive chatbot experience.
- Maintains session memory across messages.
- Powered by OpenAI’s GPT models.

---

## 📂 File
- `jarvis.py` – The chatbot script.

---

## 🔧 Installation

Clone the repository:
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

Install required libraries:
```bash
pip install openai
```

---

## 🔑 Setup API Key

⚠️ **Never hardcode your API key in the script.**

Instead, set it as an environment variable:

### Linux / macOS
```bash
export OPENAI_API_KEY="your_api_key_here"
```

### Windows (PowerShell)
```powershell
setx OPENAI_API_KEY "your_api_key_here"
```

Update the script to use the environment variable:
```python
import os
from openai import OpenAI

client = OpenAI(api_key=os.getenv("OPENAI_API_KEY"))
```

---

## ▶️ Usage
Run the chatbot:
```bash
python jarvis.py
```

Jarvis will greet you and wait for your questions.

---

## ⚠️ Important
- Do not share your API key publicly.
- Always load credentials from environment variables.
- For production use, add error handling and logging.

---

## 📜 License
This project is licensed under the MIT License.
