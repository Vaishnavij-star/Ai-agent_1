
# AI Agent From Scratch

An intelligent AI agent built using **LangChain + Anthropic (Claude)** that can perform tool-based reasoning and execute tasks dynamically.

---

## Features

*  LLM-powered reasoning using Claude (Anthropic)
*  Tool integration (custom tools support)

---

##  Tech Stack

* Python 
* LangChain
* Anthropic (Claude API)
* dotenv

---

##  Project Structure

```
.
├── main.py          # Entry point of AI agent
├── tools.py         # Custom tools for agent
├── requirements.txt # Dependencies
├── .env.example     # Sample environment variables
└── README.md        # Project documentation
```

---

##  Setup Instructions

### 1️ Clone the repository

```
git clone https://github.com/Vaishnavij-star/Ai-agent_1.git
cd Ai-agent_1
```

---

### 2️ Create virtual environment

```
python -m venv venv
venv\Scripts\activate
```

---

### 3️ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️ Setup environment variables

Create a `.env` file and add your API key:

```
ANTHROPIC_API_KEY=your_api_key_here
```

---

### 5️ Run the project

```
python main.py
```

---

##  How it Works

1. User gives input to the AI agent
2. Agent uses LLM (Claude) to understand intent
3. Based on reasoning, it selects appropriate tools
4. Executes tools and returns final response

---

##  Security

* API keys are stored securely using `.env`
* `.env` is excluded from version control
* `.env.example` is provided for reference

---

##  Author

**Vaishnavi Jaiswal**

---


