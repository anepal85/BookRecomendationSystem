# Semantic Book Recommender

This project is a semantic book recommendation system that uses natural language processing (NLP) to recommend books based on a user's query, selected category, and desired emotional tone. The system leverages a custom embedding model and a vector database to find semantically similar books.

## Features

- **Semantic Search**: Find books based on a textual description.
- **Category Filtering**: Filter recommendations by book category.
- **Emotional Tone Filtering**: Sort recommendations by emotional tone (Happy, Surprising, Angry, Suspenseful, Sad).
- **Interactive Interface**: Built with Gradio for an easy-to-use web interface.

## Screenshots

### Landing Page
![Landing Page](/screenshots/landing.png)

### Selected Books
![Selected Books](/screenshots/sample_book.png)

## Technologies Used

- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **LangChain**: Framework for developing applications powered by language models.
- **Sentence Transformers**: Library for state-of-the-art sentence embeddings.
- **Chroma**: Vector database for storing and querying embeddings.
- **Gradio**: Library for creating user-friendly web interfaces.
