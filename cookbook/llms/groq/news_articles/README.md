# News Articles powered by Groq

> Note: Fork and clone this repository if needed

### 1. Create a virtual environment

```shell
python3 -m venv ~/.venvs/aienv
source ~/.venvs/aienv/bin/activate
```

### 2. Export your `GROQ_API_KEY`

```shell
export GROQ_API_KEY=***
```

- Optional: If you'd like to use Tavily Search, export your `TAVILY_API_KEY`

```shell
export TAVILY_API_KEY=***
```

### 3. Install libraries

```shell
pip install -r cookbook/llms/groq/news_articles/requirements.txt
```

### 4. Run Streamlit App

```shell
streamlit run cookbook/llms/groq/news_articles/app.py
```

- Open [localhost:8501](http://localhost:8501) to view your Groq Researcher.

### 5. Message on [discord](https://discord.gg/4MtYHHrgA8) if you have any questions

### 6. Star ⭐️ the project if you like it.