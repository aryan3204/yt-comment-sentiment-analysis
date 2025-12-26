# yt-comment-sentiment-analysis

Python tool to fetch YouTube video comments and run transformer-based sentiment analysis using Hugging Face.

## Features

- Fetch comments from YouTube Data API v3 for a given video ID.
- Clean and preprocess comment text (lowercasing, URL/emoji removal).
- Use a Hugging Face sentiment-analysis pipeline to label each comment.
- Save results as a CSV with sentiment labels and scores.

## Tech Stack

- Python, pandas
- YouTube Data API v3
- Hugging Face `transformers` sentiment pipeline
- Jupyter Notebook (optional, for exploration)

## Getting Started

1. Clone this repository.
2. Create a virtual environment and activate it.
3. Install dependencies:
4. Create a `.env` file with your YouTube API key:
5. Run the main script (will be added soon):
## Project Structure (planned)

- `src/fetch_comments.py` – Fetch comments via YouTube Data API.
- `src/preprocess.py` – Text cleaning utilities.
- `src/sentiment_analyzer.py` – Hugging Face sentiment pipeline and CLI.
- `notebooks/` – Experiments and EDA (optional).
- `data/` – Local data (ignored in Git).

## Future Work

- Simple web UI or dashboard for visualizing sentiment.
- Support for multiple videos and channels.
- Experiment with different transformer models.



