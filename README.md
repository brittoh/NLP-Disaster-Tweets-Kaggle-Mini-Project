# NLP-Disaster-Tweets-Kaggle-Mini-Project
NLP Disaster Tweets Kaggle Mini-Project

### Brief description of the problem and data

The problem involves classifying tweets into disaster or non-disaster categories based on their content. The dataset includes a mixture of disaster-related and non-disaster-related tweets, requiring a model to accurately identify and differentiate between these two classes. The primary challenge is to develop and fine-tune machine learning models that can effectively handle the nuances of natural language in tweets, achieve high accuracy in classification, and provide meaningful insights into the key features that drive the classification results.

**Data Overview & Structure**:

The dataset has two key files: train.csv (7613 rows) and test.csv (3263 rows). It contains approximately 10,000 tweets labeled as either related to disasters or not. Each row in the dataset includes columns such as id, text (the tweet), location, keyword, and target (the label). The data needs to be pre-processed to handle missing values, stop words, and other inconsistencies before model building.

**Competition Description from Kaggle**:

"This particular challenge is perfect for data scientists looking to get started with Natural Language Processing. The competition dataset is not too big, and even if you don’t have much personal computing power, you can do all of the work in our free, no-setup, Jupyter Notebooks environment called Kaggle Notebooks."


#### Files
train.csv - the training set \ 
test.csv - the test set \
sample_submission.csv - a sample submission file in the correct format\

#### Columns
- `id` - a unique identifier for each tweet
- `text` - the text of the tweet
- `location` - the location the tweet was sent from (may be blank)
- `keyword` - a particular keyword from the tweet (may be blank)
- `target` - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)


The project includes two files: a Jupyter notebook and a requirements file. I used Python 3.11.9, and I recommend installing the packages listed in the requirements file to avoid version-related issues.
