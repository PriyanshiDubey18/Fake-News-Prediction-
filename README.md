# Fake-News-Prediction-
This project is an effort to create a Machine Learning system that can predict if "existing" and "new" news is fake or real by utilising Logistic
Regression, Decision Tree classification, Random Forest classification, and Gradient Boosting. Will also evaluate the accuracy rates of each model against one another to decide which model delivers the highest accuracy.
Furthermore, the performance of each model will be tested using three distinct datasets. The experiments demonstrate the significance of TfidfVectorizer, stemming (Potter Stemmer), Cross Validation, and other features, with random
Forest Classification achieving the greatest accuracy score among the various models.

Following are the datasets used in the project:-

1) Kaggle Fakenews dataset - Kaggle fake news dataset (25K size) has been used to evaluate the suggested technique. This dataset's primary goal was to categorise the quantity of fake and true cases. The fake news dataset's current properties are described in the paragraphs that follow.
Attributes in the specific fake news dataset
• headline- the news article's heading.
• stance- The stance taken by a news article.
• unrelated- used for the instances that are not related.
• discuss- utilised in cases where there is no relationship.
• disagree- used for entities that are incorrectly mapped.

2) COVID-19 dataset - COVID-19 dataset is considered a benchmark dataset. 10,700 social media posts and news articles about COVID-19, both legitimate and false. One of the most important recent occurrences that altered the world is COVID-19. The website of the competition's organizers contained the dataset for the CONSTRAINT COVID- 19 Fake News Detection in English challenge. It is composed of data gathered from numerous social networking and fact-checking websites, and the credibility of every blog has been personally examined. Unlike the "false" news, which was put together from tweets, posts, and articles that made COVID-19 predictions that have been shown to be incorrect, the "genuine" news was gathered from reliable sources that provided accurate COVID-19 knowledge. The original dataset includes 37,505 unique terms and 5141 phrases from
10,700 social platform news articles that are utilized in both real and fake news. The data includes 210 unique URL domains and 880 unique username handles.

3) Fake or True Dataset - his dataset includes every fake and real piece of U.S. political and financial news that has ever appeared on a social media site like Twitter or Facebook, etc. There are two CVS files in this dataset, one of which is fake. CVS and the other is True. CVS.
