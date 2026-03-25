# LangChain training

Jupyter notebooks for working through LangChain tutorials (models/prompts/parsers, memory) using the **Anthropic** API.

## Setup

1. Clone the repo.
2. Create a virtual environment and install dependencies (see each notebook’s `pip` comments, or):

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install python-dotenv anthropic langchain langchain-classic langchain-anthropic langchain-community langchain-core tiktoken
   ```

3. Copy `.env.example` to `.env` and set `ANTHROPIC_API_KEY`.

4. Open the notebooks in Jupyter or VS Code / Cursor.

## Notebooks

- `langchain_models_prompts_output_parsers.ipynb` — prompts, `ChatAnthropic`, output parsers  
- `langchain_memory.ipynb` — conversation memory types  

## License

Use and modify for your own learning.
