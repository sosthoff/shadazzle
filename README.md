# Trip Saver

This is a [Streamlit](https://streamlit.io) application that uses [langchain](https://langchain.com/) to produce a ChatGPT interface. It allows you to import, export and modify previous conversations.

This is handy if you want to force GPT to create something and then play within the world it creates. Causing it to hallucinate is fun...and hallucinating is always better with friends.

## Installation

Requires Python > 3.8 [Install](https://python.org)

You're going to need an [OpenAI API Key](https://platform.openai.com/account/api-keys)

```bash
# Your key goes in them there quotes
export OPENAI_API_KEY="..."
```

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

### Browse profiles from existing companies

```bash
streamlit run profile-browser.py
```

This is also available as a [Python Notebook](profile-browser.ipynb)