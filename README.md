# NLP Knowledge Graph

This project shows a simple example of building a tiny knowledge graph from text using Python. We take a few short sentences about a movie, preprocess them with NLP, and then turn the entities and relations into a directed graph.

## What this project does

* Stores example sentences and relations in a table using pandas
* Cleans the text with NLTK (tokenization, stopwords removal, lemmatization)
* Builds a directed graph of entities and relationships using NetworkX
* Visualizes the graph with Matplotlib

## Files

* `simple_knowledge_graph.ipynb`
  A minimal Jupyter / Colab notebook that:

  1. Downloads required NLTK resources
  2. Preprocesses a small text dataset
  3. Creates a directed graph of entities and relations
  4. Plots the knowledge graph

## Future Plans

A more detailed version of this notebook (`full_knowledge_graph_demo.ipynb`) will include:

* Step-by-step explanations for each NLP operation
* Inline comments showing where each import and resource is used
* Additional dataset examples (books, movies, and general text)
* Visual comparisons of different graph layouts and relation strengths

This future version will help visualize how knowledge graphs evolve from raw text to rich semantic structures.

## How to run

1. Install dependencies:

   ```bash
   pip install pandas networkx matplotlib nltk
   ```

2. Open the notebook:

   ```bash
   jupyter notebook simple_knowledge_graph.ipynb
   ```

3. Run all cells to see the generated knowledge graph.
