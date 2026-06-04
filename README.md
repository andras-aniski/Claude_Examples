# Claude API Training

Jupyter notebooks for learning the Anthropic Claude API.

## Setup

### 1. Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

```bash
pip install ipykernel anthropic python-dotenv
```

### 3. Configure your API key

```bash
cp .env.example .env
```

Open `.env` and replace `your_api_key_here` with your actual key from [console.anthropic.com](https://console.anthropic.com).

## Notebooks

### API Basics

| File | Topic |
|------|-------|
| `API_basics/001_api_consuming.ipynb` | Basic API request |
| `API_basics/002_multi_round.ipynb` | Multi-turn conversations |
| `API_basics/003_chat_bot.ipynb` | Interactive chat bot |
| `API_basics/004_system_prompt.ipynb` | System prompts |
| `API_basics/005_temperature.ipynb` | Temperature |
| `API_basics/006_response_streaming.ipynb` | Response streaming |
| `API_basics/007_structured_data.ipynb` | Structured data |
