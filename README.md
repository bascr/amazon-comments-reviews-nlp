# Amazon Comments Reviews - NLP

Through this project, different techniques of Natural Processing Language were employed on 
Amazon Customer Reviews. These techniques include data preprocessing, visualization, and word vectorization of each review to train various machine-learning models and classify the reviews as positive or negative. 

## Metadata

Dataset: The dataset contains **20000** sample records of **reviews** of different wireless products sell by **Amazon**. 

Dataset source: Amazon. (n.d.). Amazon Customer Reviews Dataset. [Data set]
https://s3.amazonaws.com/amazon-reviewspds/tsv/amazon_reviews_us_Wireless_v1_00.tsv.gz.

---

Due to the amount of resources for storage and processing needed for the entire dataset (7.2 GB), it was decided to work with a subset of homogenous data, that means it was selected 20000 records, 4000 record aprox. per each category of star rating (1-5).

Four models were used to classify as a binary and multiclass targets, after discretizing the rating and vectorizing each reaviews from the entire dataset.

<br>

[Click here to go to the Jupyter Notebook](https://github.com/bascr/amazon-comments-reviews-nlp/blob/main/nlp_assignment_01.ipynb)