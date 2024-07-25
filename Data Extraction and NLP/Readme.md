# NLP and Data Extraction Project
### Project Overview
This project involves extracting textual data from articles given in an input Excel file and performing text analysis to compute various metrics. The text analysis includes sentiment analysis, readability analysis, and calculation of several textual features. The results are saved in an output Excel file in a specified format.
### Approach
#### Data Extraction:
- The URLs of the articles are read from an input Excel file.
- For each URL, the article's title and text are extracted using BeautifulSoup. The text is saved to a text file named after the URL ID.

#### Text Cleaning:
- Stop words are removed from the text using a predefined list of stop words.
- The text is tokenized into words for further analysis.
#### Sentiment Analysis:
- Positive and negative word dictionaries are used to compute the Positive Score, Negative Score, Polarity Score, and Subjectivity Score.
#### Readability Analysis:
- The Gunning Fox Index is computed using the average sentence length and the percentage of complex words.
- Other metrics such as the average number of words per sentence, complex word count, word count, syllable count per word, personal pronouns count, and average word length are also calculated.
#### Saving Results:
- The results of the text analysis are saved to an output Excel file in a specified format.

### How to Run the Script
#### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.6 or higher
- pandas
- requests
- beautifulsoup4
- nltk

### Running the Script
#### Clone the Repository:
- Clone the repository to your local machine.
- Ensure that the input Excel file (Input.xlsx), the stop words directory (StopWords), and the master dictionary directory (MasterDictionary) are in the same folder as the script.
#### Prepare Google Drive (if using Google Colab):
- Mount your Google Drive and ensure the project folder is set correctly.
#### Run the Script:
- Execute the script text_analysis.py. This will read the input Excel file, process each URL, perform the text analysis, and save the results to an output Excel file named Output Data Structure.xlsx.

### Dependencies
Ensure the following packages are installed:

- pandas: Data manipulation and analysis
- requests: HTTP library for Python
- beautifulsoup4: Web scraping library
- nltk: Natural Language Toolkit for text processing

