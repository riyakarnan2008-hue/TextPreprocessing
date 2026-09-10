

Text Preprocessing using Python

About the Project

This project demonstrates the basic techniques of Text Preprocessing in Natural Language Processing (NLP) using Python. Raw text data is cleaned and transformed into a structured format for further analysis and machine learning applications.

The project is implemented using Python and Jupyter Notebook with conversation data stored in a CSV file.

Objectives

- Load text data from a CSV file.
- Clean raw conversation text.
- Convert text into lowercase.
- Remove punctuation and special characters.
- Remove unnecessary spaces.
- Compare original and processed text.
- Check for missing values.

Features

- Read conversation data from a CSV file.
- Convert text to lowercase.
- Remove unwanted characters.
- Clean extra whitespace.
- Display original and cleaned text.
- Count the number of conversations.
- Check missing values.

Technologies Used

- Python 3
- Jupyter Notebook
- CSV Module
- Regular Expressions (re)

Project Structure

Text-Preprocessing-NLP/
│
├── dataset/
│   └── raw.csv
│
├── Text_Preprocessing.ipynb
└── README.md

Dataset

The project uses a CSV file named "raw.csv" containing sample conversation data.

Example:

Conversation
Hello! How are you?
I am learning Python today.

Preprocessing Steps

1. Load the CSV dataset.
2. Read the conversation text.
3. Convert text to lowercase.
4. Remove punctuation and special characters.
5. Remove extra spaces.
6. Generate cleaned text.
7. Display the original and processed conversations.

Output

The notebook displays:

- Original conversation
- Cleaned conversation
- Total number of conversations
- Missing value count

Future Enhancements

The project can be further improved by adding:

- Tokenization
- Stop Word Removal
- Stemming
- Lemmatization
- TF-IDF Vectorization
- Word Embeddings
- Sentiment Analysis

Author

Riyavalli K
B.Sc. Computer Science with Artificial Intelligence

License

This project is created for educational and learning purposes.
