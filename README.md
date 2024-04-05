# Stream Count Prediction Model

## Description
This project demonstrates sentiment analysis and text generation tasks using Hugging Face's NLP framework. It showcases the preprocessing of text data, sentiment analysis with pipelines, and text generation using the GPT-2 model on a dataset of news articles. It serves as a tutorial for implementing NLP tasks efficiently with Hugging Face's tools.

## Overview of Notebook Content
- **Importing Libraries and Loading Data**: Import necessary libraries such as pandas for data manipulation and load the dataset from a Google Drive link.
- **Data Preprocessing**: Preprocess the text data by converting it to lowercase, removing stopwords, and combining title and description columns.
- **Sentiment Analysis using Pipeline**: Utilize the Hugging Face pipeline for sentiment analysis and analyze the sentiment of text data.
- **Text Generation using GPT-2 Model**: Showcase text generation using the GPT-2 model provided by Hugging Face and generate text based on input descriptions.
- **Results and Conclusion**: Present the results of sentiment analysis and text generation, along with the original dataset, sentiment labels, and generated text.

## Dataset
The dataset used in this tutorial contains news articles from various categories, including politics, business, entertainment, etc. It is available for download from Kaggle.

## Usage
1. Download the dataset from the provided Google Drive link and save it as `bbc_news.csv`.
2. Open the Jupyter Notebook and execute each cell sequentially.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, Hugging Face's Transformers

## Author
Shikhar Aryan
## License
This project is licensed under the [MIT License](LICENSE).
