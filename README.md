# Anthropics — Claude API Exploration

A hands-on collection of Jupyter notebooks demonstrating the capabilities of the [Anthropic Claude API](https://docs.anthropic.com/), from basic messaging to advanced features like tool use, vision, embeddings, and prompt engineering.

## Notebooks

| # | Notebook | Topic |
|---|----------|-------|
| — | `anthropics.ipynb` | Getting started — client setup, basic messaging, conversations |
| 1 | `001_tools.ipynb` | Tool use (function calling) with Claude |
| 2 | `002_images.ipynb` | Vision — image understanding and analysis |
| 2 | `002_embeddings.ipynb` | Text embeddings with VoyageAI |
| 3 | `003_vectordb.ipynb` | Vector database — chunking, embedding, and semantic search |
| 3 | `003_caching.ipynb` | Prompt caching for cost and latency optimization |
| 5 | `005_code_execution.ipynb` | Sandboxed code execution (beta) |
| 6 | `006_web_search.ipynb` | Web search tool integration |
| — | `prompt_engineering.ipynb` | Prompt engineering techniques with automated evaluation |

## Prerequisites

- Python 3.10+
- [Anthropic API key](https://console.anthropic.com/)
- [VoyageAI API key](https://www.voyageai.com/) (for embedding notebooks)

## Setup

```bash
# Clone the repository
git clone https://github.com/Dhruv18052003-web/Anthropics.git
cd Anthropics

# Install dependencies
pip install anthropic python-dotenv voyageai

# Create a .env file with your API keys
echo "ANTHROPIC_API_KEY=your-key-here" > .env
echo "VOYAGE_API_KEY=your-key-here" >> .env
```

## Usage

Open any notebook with Jupyter:

```bash
jupyter notebook
```

Each notebook is self-contained — start from the top and run cells sequentially.

## Project Structure

```
├── anthropics.ipynb          # Core API basics
├── 001_tools.ipynb           # Tool use / function calling
├── 002_images.ipynb          # Vision capabilities
├── 002_embeddings.ipynb      # VoyageAI embeddings
├── 003_vectordb.ipynb        # Vector DB + semantic search
├── 003_caching.ipynb         # Prompt caching
├── 005_code_execution.ipynb  # Code execution (beta)
├── 006_web_search.ipynb      # Web search integration
├── prompt_engineering.ipynb  # Prompt engineering + evaluation
├── dataset.json              # Sample evaluation dataset
├── images/                   # Supporting images
└── .env                      # API keys (not committed)
```

## Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **SDKs:** `anthropic`, `voyageai`
- **Config:** `python-dotenv`

## 👨‍💻 Developer

**Dhruv Umang Joshi**

* Python AI Developer
* MSc in Computer Science (Artificial Intelligence Track) @ University of Pisa (Fall 2026)
* LinkedIn: https://linkedin.com/in/dhruv-joshi-aa8195241
* GitHub: https://github.com/Dhruv18052003-web

## License

This project is for educational purposes.
