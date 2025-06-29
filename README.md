# Invoke different LLM Providers Guide

This project helps you learn how to invoke different Large Language Model (LLM) providers/models through a Jupyter notebook.

## 🛠️ Setup Instructions

1. **Setup Virtual Environment**
   ```bash
   cd /path/to/your/project   # cd downloads/use_different_llm_providers 
   python -m venv .venv       # Create virtual environment
   source .venv/bin/activate  # Activate it (Mac/Linux)
   python -m pip install --upgrade pip  # Update pip
   pip install jupyter ipykernel        # Install Jupyter and kernel
   pip install -r requirements.txt      # Install project dependencies
   ```

2. **Get API Keys**
   - OpenAI: https://platform.openai.com/api-keys
   - Google Gemini: https://aistudio.google.com/app/apikey 
   - Groq: https://console.groq.com/keys
   - OpenRouter: https://openrouter.ai/keys

3. **Configure Environment**
   - Create `.env` file in project root
   - Add your keys like:
     ```
     OPENAI_API_KEY=your_actual_key_here
     ```

4. **Start Jupyter Notebook**
   ```bash
   jupyter notebook llm_comparison.ipynb
   ```

## 📚 Step-by-Step Guide

1. Open the notebook in Jupyter
2. Run the first cell to install packages
3. Create `.env` file with your keys (DON'T SHARE THIS!)
4. Go through each provider section one by one
5. Run code cells to see different LLM responses
6. Try modifying the prompts and models

## ⚠️ Safety Tips

- Never share your .env file
- Start with free tier accounts
- Monitor your API usage
- Delete keys if compromised

## ❓ Getting Help

If stuck, try:
- Checking your API key permissions
- Verifying the .env file is in the right location
- Testing with simple prompts first
