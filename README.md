# SQL Genie 🧞‍♂️

SQL Genie is a command-line assistant that turns natural language questions into SQL queries,
and executes them against a database.

## Project Goals

- Practice building an LLM-powered "agent" that:
  - Understands natural language questions
  - Generates SQL for a known schema
  - Validates the SQL and executes it

- Produce a portfolio-ready project with clear code and documentation.

## High-Level Flow

1. User asks a question in plain English.
2. The model generates a SQL query for the target schema.
3. SQL Genie shows the generated SQL.
4. Optionally execute the query against a SQLite database and return results.
5. Handle errors and give user-friendly feedback.


## Setup (Work in Progress)

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/salehgondal/sql-genie.git
cd sql-genie
```

### 2. Create and activate a virtual environment

```bash 
python -m venv .venv
.\.venv\Scripts\Activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your Gemini API key

Create a .env file:

```bash
GOOGLE_API_KEY=your_api_key_here
```