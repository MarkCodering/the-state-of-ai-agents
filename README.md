# 🌍 The State of AI Agents

This repository showcases the **agents-as-tools** design pattern through a modular translation system built with AI agents. It demonstrates how different types of agents can collaborate to perform complex tasks—here, translating and refining multilingual messages.

---

## 🧠 Core Components

- **Translation Agents**: Handle translation tasks for specific target languages.
- **Orchestrator Agent**: Routes input messages to the appropriate translation agents based on the requested languages.
- **Synthesizer Agent**: Reviews, refines, and combines all translations into a final coherent response.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7 or higher
- [`python-dotenv`](https://pypi.org/project/python-dotenv/) for environment variable management

### 📦 Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
    ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add your API keys or configuration values.

---

## ⚙️ Usage

Run the main script to start the translation workflow:

```bash
python main.py
```

You’ll be prompted to enter a message and specify the languages for translation.

---

## 🗂 Project Structure

```
.
├── main.py             # Entry point for running the agent system
├── src/                # Core logic for agents and orchestration
├── requirements.txt    # Python dependencies
└── .gitignore          # Git exclusion rules
```

---

## 🤝 Contributing

Contributions are welcome!

* Open an issue for major changes or feature requests.
* Submit a pull request with clear descriptions and code comments.

---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for full details.

```

Let me know if you want an example `.env` section or badges (e.g. Python version, license, build status) added too.
```
