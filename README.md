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

| File | Topic |
|------|-------|
| `001.ipynb` | Basic API request |
| `002_multi_round.ipynb` | Multi-turn conversations |
| `003_chat_bot.ipynb` | Interactive chat bot |
| `004_system_prompt.ipynb` | System prompts |
