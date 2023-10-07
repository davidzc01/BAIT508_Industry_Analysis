# BAIT508_Industry_Analysis

MBAN 2024 BA1 Team 32

David Chen | Student Number: 30409156 | Email: zeyuchen97@hotmail.com

Wanting Xu | Student Number: 81971392 | Email: xuwanting.hk@gmail.com

## Project Overview

### Project Objectives

The goal of this project is to conduct an in-depth analysis of public US firms within selected industry sector(s) using various data analyses and natural language processing (NLP) techniques that we learned in BAIT 508. Each team will choose at least one industry sector to investigate and utilize multiple datasets to extract valuable industry insights from the data.

### Team and Roles
- Data processing, model training, and visulization : Collaborated contribution (led by David Chen)
- Data analysis and write-up: Collaborated contribution (led by Wanting Xu)
### Technologies Used
- Python
- Jupyter Notebook
- Visual Studio Code
- Git/Github
- ChatGPT
### Credits
This is a course project for BAIT 508 Business Analytics Programming at the Sauder School of Business, University of British Columbia. The project is prepared by professor Dr. Gene Moo Lee and TAs for this course (Jaecheol Park, Xiaoke Zhang) in 2023W Period 1. The instruction team provides the datasets for this project, and some of the functions including `DocumentSimilarity.py` are adapted from the course materials.
## Project Setup
### Dependencies
The project is running on Python 3.11.4. The following dependencies are required to run the code in this project.
#### Python Packages
- `pandas` for reading and manipulating the datasets as data frames.
- `string` for string manipulation.
- `nltk` for natural language processing.
- `sklearn` for machine learning.
- `matplotlib` for data visualization.
- `warnings` for ignoring warnings.
- `os` for file path manipulation.
- `collections` for counting.
- `wordcloud` for word cloud visualization.
- `gensim` for `Word2Vec` model.

#### Other Dependency
- `DocumentSimilarity.py`: one wrapper to compute firm-level embedding and similarity based on the word2vec model prepared by the BAIT 508 instruction team.
### Datasets
This project uses 3 datasets provided by the BAIT 508 instruction team: `2020_10K_item1_full.csv`, `major_groups.csv`, and `public_firms.csv`. you need to obtain or create these datasets and put them in the `data` folder in the project root directory in order to run the code in this project. The datasets are not included in this repository due to the size limit.
  - `2020_10K_item1_full.csv`: contains a sample of 5,988 firms and their “item 1” content in their 10-K reports in the year 2020. The dataset contains following columns:
    - `cik`: the unique identifier for each firm.
    - `year`: the fiscal year of the 10-K report.
    - `name`: the name of the firm.
    - `item1`: the content of “item 1” in the 10-K report.
    - `gvkey`: the unique identifier for each firm.
  - `major_groups.csv`: contains 83 major industry groups' corresponding codes and their descriptions. The dataset contains following columns:
    - `major_group`: corresponding code to the major industry group, the code corresponds to the first two digits of each firm’s SIC code.
    - `description`: the name of the industry group.
  - `public_firms.csv`: contains the 209212 records of public firms. The dataset contains following columns:
    - `gvkey`: the unique identifier for each firm.
    - `fyear`: fisical year in which the financial data was reported.
    - `location`: the location (country / region) of the firm.
    - `conm`: the name of the firm.
    - `ipodate`: the date of the firm’s initial public offering.
    - `sic`: the Standard Industrial Classification (SIC) code of the firm.
    - `prcc_c`: the closing price of the firm’s common stock in that year.
    - `ch`: the amount of cash and cash equivalents of the firm.
    - `ni`: the net income of the firm.
    - `assets`: the assets of the firm.
    - `sale`: total sales or revenue generated by the company.
    - `roa`: the return on assets of the firm.

##  Project Explaination by Steps
### Part 1. Quantitative Analysis of the Industry Sector

#### A. Industry Sector Selection and Data Filtering

    1.
    2.
    3.
        a.
        b.
        c.

#### B. Preliminary Analysis
    1.
    2.
    3.
    4.
    5.
    6.


### Part 2. Text Analysis on the Industry Sector
#### C. Text Cleaning
    1.
    2.
    3.

#### D. Keyword Analysis
    1.
    2.
    3.

#### E. Word Embedding
    1.
    2.


### Part 3. Comprehensive Analysis of One Sample Firm
#### F. Firm Analysis and Strategy Suggestion
    1.
    2.
    3.

