# My Chromadb project


A collection of practical experiments exploring artificial intelligence, natural language processing, embeddings, and retrieval-augmented generation (RAG).

## spaCy Word Embeddings Visualization

This experiment uses spaCy's `en_core_web_md` model to explore semantic relationships between words.

**Technologies:**
- Python and uv
- spaCy with 300-dimensional word embeddings
- Scikit-learn PCA for dimensionality reduction
- NumPy and Pandas
- Matplotlib for visualization
- Jupyter Notebook

**Experiments:**
1. Extract word embeddings for 20 words.
2. Reduce 300-dimensional vectors to 2 dimensions using PCA.
3. Visualize words in a scatter plot.
4. Calculate cosine similarity between words.
5. Display a semantic similarity heatmap.
6. Find the most similar words.

## Getting Started

Install project dependencies:

```bash
uv sync
```

Install the spaCy language model:

```bash
uv run python -m spacy download en_core_web_md
```

Launch JupyterLab:

```bash
uv run jupyter lab
```

Open `spacy_word_embeddings.ipynb` to run the experiment.
