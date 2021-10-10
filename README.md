# Repository to host sample data and code used for the paper `Social Status and Novelty Drove the Spread of Online Information During the Early Stages of COVID-19`

The repository contains 3 notebooks
- `quantifying_novelty.ipynb`: Contains the algorithm that was used to calculate the tweet-level novelty
- `social_dimensions_classification.ipynb`: Contains the process of training machine learning classifiers to predict whether a tweet belongs to a specific category
- `regressions.ipynb`: Contains the code for all the regressions that were mentiontioned in the paper

The repository contains 5 datasets
- `annotated_tweets.csv`: The results of the manual annotations (`status_id` and social dimensions)
- `annotated_tweets_data.csv`: The tweet text collected from the Twitter API for the annotated tweets in `annotated_tweets.csv`
- `dataset_for_regressions_sample.csv`: A sample of the final dataset that was used for the regressions. Due to the size of the full dataset, we couldn't include the whole dataset in GitHub. The full dataset can be found at:
- `raw_tweets_sample.csv`: Random sample of tweets. Used in `quantifying_novelty.ipynb`. Due to the size of the full dataset, we couldn't include the whole dataset in GitHub. The full dataset can be found at:
- `tweets_to_predict.csv`: Sample of tweets to apply the machine learning models build in `social_dimensions_classification.ipynb`
