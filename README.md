# AGENTICAI

A workspace for building agentic AI applications with [LangChain](https://python.langchain.com/).

## Setup

```bash
# Create and activate the virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

Create a `.env` file in the project root with your API keys, for example:

```
OPENAI_API_KEY=your-openai-api-key
```

## Project structure

```
.
├── langchain/         # LangChain experiments and code
├── requirements.txt   # Python dependencies
├── LICENSE            # MIT License
└── README.md
```

> Note: don't add an `__init__.py` to `langchain/` — it would shadow the installed `langchain` package.

## License

MIT — see [LICENSE](LICENSE).
