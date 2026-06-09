<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=500&color=6366F1&center=true&vCenter=true&width=600&lines=📸+Screenshot+Error+Diagnoser;AI-Powered+Error+Detection;Snap.+Analyze.+Fix." />
  
  <img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python&color=3776AB" />
  <img src="https://img.shields.io/badge/Flask-3.0-black?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/OpenRouter-API-purple?style=for-the-badge&logo=openai&color=8B5CF6" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
  
  <img src="https://komarev.com/ghpvc/?username=vishnu-psvpec&label=👁️+VIEWS&color=6366f1&style=flat-square" />

</div>

---

## 🎯 **Problem Statement**

> *"Developers waste hours typing error messages manually. What if you could just take a screenshot and get instant fix steps?"*

**Screenshot Error Diagnoser** combines:
- 🖼️ **Vision LLM** - Extracts error text from screenshots
- 📚 **RAG** - Matches errors against knowledge base
- 🔧 **AI Generation** - Produces actionable fix steps

---

## ✨ **Features**

| Feature | Description |
|---------|-------------|
| 📸 **Screenshot Upload** | Drag & drop or click to upload |
| 👁️ **Vision LLM** | Extracts exact error text from images |
| 🧠 **RAG Knowledge Base** | Stores & matches common errors |
| 🔄 **Auto-Learning** | New errors auto-added to KB |
| 💰 **Credits Tracking** | Real-time token usage & cost |
| 📜 **Diagnosis History** | Stores all previous diagnoses |
| 🧩 **Explain Simply** | Breaks down errors for beginners |
| 🔍 **Similar Errors** | Finds related issues in KB |
| 📋 **Copy Solution** | One-click copy to clipboard |
| 🎨 **Premium UI** | Glassmorphism design with animations |

---

## 🏗️ **Architecture**
📸 Upload → 👁️ Vision LLM → 📚 RAG Match → 🔧 Generate Fix → 📋 Display Results
↓ ↓
🗄️ Knowledge Base 🔄 Auto-Learn

text

**Tech Stack:**
- Backend: Flask 3.0 (Python 3.11+)
- AI Models: OpenRouter (Gemini/Llama free tier)
- Database: JSON (no setup required)
- Frontend: HTML5, CSS3, JavaScript

---

## 🚀 **Quick Start**

```bash
# Clone repository
git clone https://github.com/vishnu-psvpec/06-screenshot-error-diagnoser.git
cd 06-screenshot-error-diagnoser

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your OpenRouter API key

# Run the application
python app.py
Open: http://localhost:5001

📖 How It Works
Upload Screenshot - Drag & drop any error screenshot

AI Extraction - Vision LLM reads the error message

RAG Matching - Matches against knowledge base

Fix Generation - AI generates numbered fix steps

Auto-Learning - New errors added to KB automatically

🎮 Examples
<details> <summary><b>🐍 Python Module Error</b></summary>
text
ModuleNotFoundError: No module named 'flask'
Output:

Install Flask: pip install flask

Verify installation: pip list | grep flask

Check virtual environment is activated

Add flask to requirements.txt

</details><details> <summary><b>🔌 Port Conflict</b></summary>
text
Error: listen EADDRINUSE: address already in use :::5000
Output:

Find process: lsof -i :5000

Kill process: kill -9 <PID>

Use different port: PORT=5001 npm start

</details><details> <summary><b>🎨 Adobe Error</b></summary>
text
Configuration error. Error: 16
Output:

Close all Adobe apps and Creative Cloud

Restart your computer

Run Adobe Creative Cloud Cleaner Tool

Reinstall the application

</details>
📁 Project Structure
text
06-screenshot-error-diagnoser/
├── app.py                 # Flask backend + AI
├── templates/
│   └── index.html        # Web UI
├── static/
│   ├── style.css         # Styling
│   └── script.js         # Frontend logic
├── knowledge_base.json   # RAG knowledge base
├── requirements.txt      # Dependencies
├── tests/
│   └── test_app.py      # Unit tests
└── sample_data/
    └── sample_error.png  # Example screenshots
🧪 Run Tests
bash
pytest tests/ -v
text
✅ test_rag_finds_econnrefused PASSED
✅ test_rag_finds_module_error PASSED
✅ test_rag_returns_empty_for_unknown PASSED
✅ test_knowledge_base_has_entries PASSED
✅ test_app_index_returns_200 PASSED
🤖 AI Capabilities
Capability	Status
Vision LLM (Error Extraction)	✅
RAG (Knowledge Base Matching)	✅
External API Integration	✅
Agent Loop (Extract→Match→Generate→Learn)	✅

🔧 Environment Variables
env
OPENROUTER_API_KEY=your_api_key_here
OPENROUTER_MODEL=openrouter/free
OPENROUTER_API_URL=https://openrouter.ai/api/v1
🐛 Troubleshooting
Issue	Solution
API Key error	Check .env file exists
Port in use	Change port in app.py (last line)
Empty response	Wait 10-20 seconds, free tier has rate limits
📊 Evaluation Criteria
✅ Working code using AI assistants

✅ Building AI Agents

✅ Service/API Integration

✅ End-to-End Execution

✅ Code Quality & Documentation

