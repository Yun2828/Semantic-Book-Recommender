# Semantic Book Recommendation System
## Overview

This project is a content-based book recommendation system built with Large Language Models (LLMs), vector search, and sentiment analysis.

It uses book descriptions to create semantic embeddings, allowing users to:

- Discover similar books based on natural language queries

- Filter recommendations by category (Fiction, Non-Fiction, Children's Fiction, Children's Non-Fiction)

- Sort results by emotional tone (Happy, Sad, Suspenseful, etc.)

Explore results through an interactive Gradio dashboard

## Features

- Text Cleaning & Preprocessing: Data prepared from Kaggle’s 7k Books dataset

- Vector Database with LangChain + ChromaDB

- Zero-Shot Classification with Hugging Face models

- Sentiment Analysis with fine-tuned Roberta models

- Interactive Dashboard with book covers, titles, authors, and truncated descriptions
