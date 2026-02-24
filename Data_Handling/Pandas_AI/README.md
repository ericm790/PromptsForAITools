# PandasAI — Prompt Guide

## Overview
PandasAI is a Python library that integrates large language models with the pandas data analysis library, allowing users to interact with their data using natural language. It translates conversational queries into pandas code, enabling data exploration, cleaning, visualization, and analysis without writing code manually.

## How to Use

### System Prompt
1. Use `System_Prompt.txt` as the system message when configuring PandasAI's underlying LLM.
2. Or adapt it for use with any LLM-powered data analysis workflow (e.g., ChatGPT + Code Interpreter, LangChain agents).

### User Prompts
- Use these prompts when working with tabular data (CSVs, Excel files, databases).
- Always describe your dataset structure (columns, types, size) for best results.
- Specify the exact analysis or transformation you need.

## Tips for Best Results
- **Describe your data** — include column names, data types, and row counts for accurate code generation.
- **Be specific about output** — ask for tables, charts, or summary statistics explicitly.
- **Iterate step-by-step** — start with exploration, then cleaning, then analysis for complex tasks.
- **Request the code** — ask to see the generated pandas code so you can learn and verify.
- **Handle large datasets** — mention dataset size so the AI can optimize for memory and performance.
