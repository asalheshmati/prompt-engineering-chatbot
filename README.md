# Prompt Engineering Lab

This lab walks through prompt design, prompt iteration, and evaluation using a Jupyter notebook.

## What's Included

- `prompt_engineering_lab.ipynb`
- `prompt_engineering_chatbot.ipynb`
- `.env` for local API configuration

## Lab Goals

- Build baseline prompts for sentiment analysis, product description generation, and data extraction
- Run prompts multiple times to measure consistency
- Rewrite prompts with clearer instructions, output constraints, and structured formats
- Compare earlier versions against improved versions
- Test prompt variations and document what works best

## Notebook Flow

- Part 1: Start simple with baseline prompts
- Part 2: Add structure and constraints
- Part 3: Rewrite prompts for clearer output
- Part 4: Add few-shot examples, Chain-of-Thought, and schema-driven prompting
- Part 5: Test task variations and compare final results

## Requirements

- Python 3.11+
- Jupyter Notebook
- `openai`
- `python-dotenv`

## Setup

1. Create or update your `.env` file.
2. Add your OpenAI API key:

```env
OPENAI_API_KEY=your_api_key_here
```

3. Install dependencies if needed:

```bash
pip install openai python-dotenv jupyter
```

## How to Run

- Open `prompt_engineering_lab.ipynb` in Jupyter or VS Code.
- Run the setup cells first.
- Follow the notebook sections in order.
- Review the comparison tables and checkpoint outputs after each iteration.

## Notes

- The notebook includes an offline fallback path in this workspace because outbound API access may be blocked in some environments.
- If you run the notebook with live API access, the prompts will use the OpenAI client normally.
- Do not commit your `.env` file or API key to version control.

## Expected Outcome

- You should be able to compare prompt versions by consistency, output format, and task behavior.
- By the final iteration, the prompts should be more stable, more structured, and easier to evaluate across variations.
