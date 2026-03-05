# LangChain Experiments

This repository contains my experiments with **LangChain, OpenAI, local LLMs (Ollama) and HuggingFace** while learning Retrieval-Augmented Generation (RAG) and LLM application development.

## Topics Covered

- LangChain fundamentals
- Prompt chains
- Document embeddings
- Vector databases (Chroma,FAISS)
- Local LLM inference with Ollama
- OpenAI API integration

## Project Structure

```
LangChain/
│
├── notebooks/          # Jupyter notebooks with experiments
├── scripts/            # Python scripts
├── requirements.txt    # Project dependencies
├── README.md
```

## Setup

Clone the repository:

```bash
git clone https://github.com/VigneshwariJayaprakash/langchain-learning.git
cd langchain-learning
```

Create environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

## Author

**Vigneshwari Jayaprakash**  
MS Data Science – Arizona State University