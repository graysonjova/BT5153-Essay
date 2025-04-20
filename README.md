# BT5153 Group Project

## Overview
This project aims to develop an automated essay grading system using AI models. The system utilizes a dataset of essays and a specific grading rubric to evaluate student submissions.

## Project Structure
- **BT5153-Essay/**: Contains the main code and resources for the project.
  - **BT5153.ipynb**: Jupyter Notebook with the implementation of the grading system, including functions for loading essays, generating rubrics, and grading.
  - **scraped_essays.csv**: Dataset of essays used for grading and analysis.
  - **wangcongGrading.pdf**: Document containing the specific marking scheme used to generate a generalized rubric.

## Requirements
- Python 3.x
- Required libraries: requests, sqlite3, datetime, PyPDF2, re, json, os, pandas, langchain_community, sklearn, google.genai, fitz (PyMuPDF)

## Usage
1. Load the dataset of essays from `scraped_essays.csv`.
2. Use the PDF document `wangcongGrading.pdf` to generate a generalized rubric.
3. Grade essays using the functions defined in `BT5153.ipynb`.

## Installation
Install the required libraries using pip:
pip install requests sqlite3 PyPDF2 pandas langchain_community sklearn google.genai PyMuPDF

## License
This project is licensed under the MIT License.