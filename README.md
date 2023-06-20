# Movies-Transcript-Analysis
Exploring natural language processing techniques to extract insights and patterns from movie transcripts

## Features
- Scrapes movie transcripts from "scrapsfromtheloft.com" using the `requests` and `BeautifulSoup` libraries.
- Creates a dataframe for storing the transcript data.
- Preprocesses the transcripts by removing stop words, punctuations, and other unnecessary elements using the `re`, `string`, and `contractions` libraries.
- Tokenizes the preprocessed data using the `CountVectorizer` and creates a document-term matrix.
- Stores the resultant corpora as pickle files for further analysis.
- Performs various analyses on the data, including generating word clouds, calculating words per minute, and counting bad words, scary words and violent words.

## Dependencies
- Python 3.x
- `requests`
- `BeautifulSoup`
- `re`
- `string`
- `contractions`
- `nltk`
- `scikit-learn`
- `matplotlib`
- `wordcloud`
