# Product Dashboard Analysis

A Streamlit web app that generates a structured product analysis report using the OpenRouter/OpenAI API.

## Features

- Enter any product name
- Generate a product analysis report in markdown format
- Includes demand, customer profile, marketing strategy, feasibility, business model, and launch plan
- Built with Python and Streamlit

## Tech Stack

- Python
- Streamlit
- OpenAI Python SDK
- python-dotenv

## Project Structure

- `app.py` - Streamlit application
- `requirements.txt` - Python dependencies
- `.env` - local environment variables (not committed)
- `scripts.md` - notes or commands used during development

## Setup

1. Create and activate a virtual environment
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file with:

```env
OPENROUTER_API_KEY=your_openrouter_key_here
OPENROUTER_MODEL=openai/gpt-4o-mini
```

4. Run the app:

```bash
streamlit run app.py
```

## Notes

- The app reads environment values from `.env`.
- Make sure your OpenRouter API key is valid and has access to the selected model.
- `.env` is ignored by git for security.
