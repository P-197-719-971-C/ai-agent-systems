# Gemini LangGraph Project

A simple LangGraph implementation using Google's Gemini API.

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Create virtual environment
```bash
python -m venv myvenv
source myvenv/bin/activate  # On Windows: myvenv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up environment variables
Create a `.env` file in the project root:
```bash
GEMINI_API_KEY=your_actual_api_key_here
```

Get your API key from: https://aistudio.google.com/app/apikey

### 5. Run the notebook
```bash
jupyter notebook test_gemini.ipynb
```

## Project Structure
```
.
├── test_gemini.ipynb    # Main notebook
├── .env.example         # Template for environment variables
├── .gitignore          # Files to ignore in git
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## Features
- LangGraph workflow with Gemini API
- Token counting functionality
- Environment variable management