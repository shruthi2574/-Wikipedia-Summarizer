# 🧠 Wikipedia Summarizer

A simple and interactive command-line application built with Python.  
It allows users to input any topic and returns a clean, concise summary using the Wikipedia API.

---

## 🔍 Features

- 🔎 Summarize any topic from Wikipedia  
- 📚 Get brief, readable summaries  
- ⚠️ Handles broad, ambiguous, or misspelled queries gracefully  
- 🌐 Uses the `wikipedia` Python library to access real-time data  

---

## 🧰 Tech Stack

| Tool            | Description                          |
|-----------------|------------------------------------|
| Python          | Core programming language           |
| wikipedia       | Python wrapper for Wikipedia's API |
| JSON            | For handling API responses          |
| Google Colab / VS Code | Development environments       |
| Git & GitHub    | Version control and publishing      |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed  
  👉 [Download Python](https://www.python.org/downloads/)

---

### 🔧 Installation & Running

1. **Install the required library:**

   ```bash
   pip install wikipedia
Run the application:

bash
Copy
Edit
python wikipedia_summarizer.py
💡 How It Works
Prompts user to enter any topic

Uses Wikipedia API to fetch a brief summary

Displays the summary or gives suggestions if the topic is ambiguous

💬 Example Output
text
Copy
Edit
🔎 Enter a topic to summarize from Wikipedia: python

📘 Summary of 'Python':
Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with its use of significant indentation...

🔎 Enter a topic to summarize from Wikipedia: love

⚠️ The topic 'love' is ambiguous.
Here are some options:
- Love (emotion)
- Love (film)
- Love (TV series)

Try being more specific.
📂 Project Structure
Copy
Edit
wikipedia-summarizer/
├── wikipedia_summarizer.py
└── README.md
🙋‍♀️ Author
Gugulothu Shruthi
B.Tech, CSE — Narayanamma Institute of Technology
✉️ gugulothushruthi@gmail.com


