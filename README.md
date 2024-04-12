README_DESCRIPTION = """
## Twitter Sentiment Analysis with Hugging Face Transformers

### Overview:
This project demonstrates how to perform sentiment analysis on tweets using the Hugging Face Transformers library. Sentiment analysis aims to determine the sentiment expressed in a piece of text, such as positive, negative, or neutral.

### Features:
- Preprocesses tweets to handle mentions and URLs.
- Utilizes a pre-trained sentiment analysis model (Twitter-RoBERTa) from the Hugging Face Transformers library.
- Prints sentiment labels and scores for the analyzed tweets.
- Makes a decision on the sentiment based on the highest score.

### Dependencies:
- Python 3.x
- transformers library
- scipy library

### Usage:
1. Install the required dependencies (`transformers`, `scipy`).
2. Modify the `tweet` variable with the tweet text you want to analyze.
3. Run the script to perform sentiment analysis on the tweet.
4. View the sentiment labels, scores, and the decision based on the highest score.

### Example:
```python
tweet = 'I am happy to learn NLP 😉'
