# Python-AI-training

Learning Python and AI from scratch, one project at a time.

## Project: Text Summarizer

A web app that summarizes long articles, built in Python.

- Model: sshleifer/distilbart-cnn-12-6 (Hugging Face)
- Interface: Gradio
- Handles long text by splitting it into chunks, summarizing each, then combining the results

### How to run
Open `my_summarizer.ipynb` in Google Colab and run all cells in order.

### Limitations
Small model, so it may miss details. Works best on news-style English text.
