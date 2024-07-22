# TextInsight: Article Extraction and Analysis

**TextInsight** is a Python-based project designed to extract and analyze textual data from articles. It performs sentiment analysis, readability assessments, and other textual metrics on content retrieved from specified URLs.

## Project Overview

The **TextInsight** project aims to automate the process of extracting meaningful insights from textual data. It extracts content from given URLs, computes various sentiment metrics, evaluates readability, and assesses text complexity. The results are organized and saved in an Excel file for easy review.

## Key Features

- **Data Extraction**: Extracts article text from URLs, ignoring headers, footers, and other non-article content.
- **Sentiment Analysis**: Calculates Positive Score, Negative Score, Polarity Score, and Subjectivity Score using predefined dictionaries.
- **Readability Analysis**: Computes metrics such as Average Sentence Length, Percentage of Complex Words, and FOG Index.
- **Text Metrics**: Evaluates Complex Word Count, Word Count, Syllables per Word, Personal Pronouns, and Average Word Length.
- **Output**: Saves results in an Excel file for comprehensive analysis.

## Tools and Libraries

- **Python**: Core language for data extraction and analysis.
- **BeautifulSoup**: Used for web scraping to extract article text.
- **NLTK**: Provides tools for text processing and sentiment analysis.
- **TextBlob**: Used for sentiment polarity and subjectivity calculations.
- **Pandas**: Handles data manipulation and output formatting.
- **Syllapy**: Counts syllables in words (if applicable).
