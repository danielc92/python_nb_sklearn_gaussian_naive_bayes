# Text Classification (python_nb_sklearn_gaussian_naive_bayes)
This project contains various notebooks applying text classification using multipolynomial naive bayes, vectorization and gridsearch within a `jupyter notebook` environment. Execution of this project relies quite heavily on `sklearn` library from `python3`.

# Before you get started
Make sure you have a read or general understanding to the concepts and methods below before getting started;
- Understanding how to use jupyter notebooks
- Application of naive bayes model
- Train test split concept
- Cross validation
- Confusion matrices
- Text manipulation, vectorization, term frequency and inverse document frequency

## Notebooks
1. **gaussian-naive-bayes-example.ipynb** - Basic Naive Bayes examples.
2. **gaussian-naive-bayes-mpg.ipynb** - Implementation of Naive Bayes using `sklearn` on the **mpg** dataset.
3. **multinomial-naive-bayes-20newsgroups.ipynb** - Implementation of Multinomial Naive Bayes using `sklearn` on the **20newsgroups** dataset.
4. **multinomial-naive-bayes-amazon.ipynb** - Implementation of Multinomial Naive Bayes using `sklearn` on the **amazon_cells_labelled** dataset.
5. **multinomial-naive-bayes-imdb-gridsearch.ipynb** - Implementation of Multinomial Naive Bayes using `sklearn` on the **imdb_labelled** dataset.
6. **multinomial-naive-bayes-spam-gridsearch.ipynb** - Implementation of Multinomial Naive Bayes using `sklearn` on the **spam.xlsx** dataset.
7. **multinomial-naive-bayes-yelp.ipynb** - Implementation of Multinomial Naive Bayes using `sklearn` on the **yelp_labelled** dataset.

## Directories
1. **sentiment labelled sentences** - contains yelp, amazon and imdb review data.
2. **20_newsgroups** - contains raw 20_newsgroups dataset.
3. **20_newsgroups_processed** - contains csv version of 20_newsgroups dataset.

# Installation
**Requirements**
- `sklearn`
- `pandas`
- `numpy`
- `jupyter`

```sh
pip install jupyter pandas numpy sklearn
```

# Contributors
- Daniel Corcoran

# Sources
- [Example of pipeline grid search](https://scikit-learn.org/stable/auto_examples/model_selection/grid_search_text_feature_extraction.html)
- [sklearn documentation](https://scikit-learn.org/stable/index.html)
- [guide from towards datascience](https://towardsdatascience.com/machine-learning-nlp-text-classification-using-scikit-learn-python-and-nltk-c52b92a7c73a)
- [Kaggle IMDB data](https://www.kaggle.com/utathya/imdb-review-dataset)
- [Sentiment labelled sentences dataset](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences)
- [SMS Spam Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
