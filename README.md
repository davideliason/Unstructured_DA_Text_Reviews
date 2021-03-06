# Unstructured Data Analysis
## [David Eliason](http://www.davideliason.me)
### Intro
There is word level information:
- tokenization
- bag of words
- stemming
- lemmatization
- TFI-DF
There is phrase level information:
- n-grams
There is part of speech information:
- POS
- Parse Tree

Usually we have all this textual data and there are too many dimensions, or features - our machine learning models work more efficiently and quickly if we have fewer of those. So, we need to enact dimension reduction. Then, we can build a model that can be used for interpretation of the data and/or used for prediction. And that's the main draw of these kinds of algorithms- to better understand and to predict.

### Format
First we have to change xlsx to csv for pandas

### Tokenization
This is where we split sentences into words (or, tokens)
- We can use a vanilla tokenizer, which I did first
- We can use nltk's WhiteSpaceTokenizer to break a sentence into tokens (words) without whitespaces