# Shedazzle Answer-O-Tron

This is a [Streamlit](https://streamlit.io) application that uses [Langchain](https://langchain.com/) to produce a Chat interface. It allows you to import, export and modify previous conversations.

This is handy if you want to force an LLM to create something and then play within the world it creates. Causing it to hallucinate is fun...and hallucinating is always better with friends.

## Installation

Requires Python > 3.8 [Install](https://python.org)

You're going to need an [Google PaLM API Key](https://makersuite.google.com)

```bash
python -m venv venv
source ./venv/bin/activate
python -m pip install -r requirements.txt
```

## Run the apps


### Run existing "trips" or create new ones

```bash
streamlit run hallucinate.py
```

### Explore some solutions

```bash
streamlit run playground.py
```

This is also available as a [Python Notebook](profile-browser.ipynb)
