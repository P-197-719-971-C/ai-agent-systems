# Gemini LangGraph Project

LangGraph implementation with Google's Gemini API.

## Setup

Built with Python 3.12 and [uv](https://github.com/astral-sh/uv) on macOS.
```bash
# Clone and navigate
git https://github.com/P-197-719-971-C/ai-agent-systems.git
cd ai-agent-systems

# Install dependencies
uv pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Add your Gemini API key to .env
```

Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

## Usage
```bash
jupyter notebook test_gemini.ipynb
```

## Structure
```
├── test_gemini.ipynb    # Main workflow
├── requirements.txt     # Dependencies
├── .env.example         # Environment template
└── .gitignore          
```

## Security

`.env` is gitignored. Never commit API keys.

If accidentally committed:
```bash
git rm --cached .env
git commit -m "Remove .env from tracking"
# Rotate your API key immediately
```

Ensure `.gitignore` includes:
```
.env
venv/
myvenv/
__pycache__/
*.pyc
.ipynb_checkpoints/
.DS_Store
```

## Features

- LangGraph workflow integration
- Token counting
- Environment-based configuration