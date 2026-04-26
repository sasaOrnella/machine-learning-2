# Web Scraping and NLP Text Classification
This project demonstrates a complete NLP workflow, including web text data collection, text preprocessing, feature extraction, and text classification. The web scraping module collects structured text information from static web pages, using Japanese financial news and official announcement websites as examples. The NLP module applies traditional machine learning and deep learning models to classify text data and compare model performance.

### Main Components

1. Web Text Collection  
   - Collected text information from static web pages using requests and BeautifulSoup.
   - Extracted dates, titles, URLs, text summaries, and PDF links.
   - Converted unstructured web content into structured CSV files.

2. Text Preprocessing and Feature Engineering  
   - Cleaned raw text data.
   - Applied tokenization, stopword removal, and lemmatization.
   - Built TF-IDF features and Word2Vec embeddings.

3. Text Classification  
   - Built Logistic Regression as a baseline model.
   - Implemented CNN/TextCNN models for neural text classification.
   - Compared model performance using accuracy and visual analysis.
