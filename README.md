# NLP_Crypto

The analysis looks applies natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. The analysis applies fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

## Sentiment Analysis

Utilizing the News API to pull the latest news articles for bitcoin and ethereum. Natural language procesing is applied to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. 

The sentiment is scored using VADER Sentiment, a rule based system to score the sentiment polarity of human space as positive, neutral or negative based on a set of rules and a lexicon. At the time of the analysis:

- Ethereum had the highest mean positive score
- Ethereum had the highest compound score
- Ethereum had the highest positive score 

## Tokenizer

Utilizing NTLK and Python to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Top 10 words for Bitcoin:
- 'bitcoin', 42
- 'satoshi', 24
- 'nakaboto', 24
- 'char', 20
- 'another', 13
- 'robot', 12
- 'colleague', 12
- 'writes', 12
- 'every', 12
- 'fucking', 12
 
 
Top 10 words for Ethereum:
- 'char', 17
- 'bitcoin', 12
- 'satoshi', 6
- 'nakaboto', 6
- 'another', 4
- 'crypto', 4
- 'robot', 3
- 'colleague', 2
- 'writes', 3
- 'btc', 3
 
 ## Named Entity Recognition
 Last part of the analysis requires building a named entity recognition model for both coins and visualize the tags using SpaCy.
