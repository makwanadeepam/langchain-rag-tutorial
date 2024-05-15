# Langchain RAG Tutorial

Install dependencies.

```python
pip install -r requirements.txt
```

Replace "YOUR-API-KEY" in files query_data.py and create_database.py with OpenAI API key.

Create the Chroma DB.

```python
python create_database.py
```

Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
```

You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.
