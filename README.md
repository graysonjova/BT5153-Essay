# BT5153 Group Project

## Overview
This project aims to develop an automated essay grading system using AI models. The system utilizes a dataset of essays and a specific grading rubric to evaluate student submissions. The project also includes exploratory data analysis, essay augmentation, and prompt engineering.

## Project Structure
- **BT5153-Essay/**: Contains the main code and resources for the project.
  - **BT5153.ipynb**: Jupyter Notebook with the implementation of the grading system, including:
    - Functions for loading essays.
    - Generating rubrics from a marking scheme.
    - Grading essays using machine learning models.
    - Exploratory data analysis and visualization.
  - **eda_final.ipynb**: Notebook for exploratory data analysis, including visualizations of essay scores, word counts, and grammar errors.
  - **augment.ipynb**: Notebook for augmenting essays by generating poor-quality and off-topic versions.
  - **gp_webscraper.ipynb**: Notebook for scraping GP model essays from the specified website and saving them to a CSV file.
  - **scraped_essays.csv**: Dataset of essays used for grading and analysis.
  - **grading_rubrics.pdf**: Document containing the specific marking scheme used to generate a generalized rubric.

## Requirements
- Python 3.x
- Required libraries: requests, sqlite3, datetime, PyPDF2, re, json, os, pandas, langchain_community, sklearn, google.genai, fitz (PyMuPDF), matplotlib, seaborn, nltk, wordcloud, textstat, sentence-transformers, groq, ollama

## Usage
1. Load the dataset of essays from `scraped_essays.csv`.
2. Use the PDF document `grading_rubrics.pdf` to generate a generalized rubric.
3. Run the Jupyter Notebooks:
   - **BT5153.ipynb**: Main implementation of the grading system.
   - **retriever.ipynb**: Build a vector store and retrieve essays based on similarity.
   - **eda_final.ipynb**: Perform exploratory data analysis on the dataset.
   - **BT5153_prompt_engineering.ipynb**: Generate rubrics and grade essays using AI models.
   - **augment.ipynb**: Augment essays by generating poor-quality and off-topic versions.
   - **gp_webscraper.ipynb**: Scrape GP model essays and save them to a CSV file.


## Installation
Install the required libraries using pip:
```
pip install requests sqlite3 PyPDF2 pandas langchain_community sklearn google.genai PyMuPDF matplotlib seaborn nltk wordcloud textstat sentence-transformers groq ollama
```

## License
This project is licensed under the MIT License.
