# NLP-classification-with-disaster-Tweets

Link to the [Kaggle competition](https://www.kaggle.com/c/nlp-getting-started/overview)

Link to my [Kaggle profile](https://www.kaggle.com/jvmd95/competitions?sortBy=grouped&group=entered&page=1&pageSize=20)

NLP classification using state of the art model BERT through TFHUB. Check the notebook for a basic explanation of BERT.


# Score

Accuracy score of 0.83537.

Position: 602 out of 2974. Top 20%

We can see the power of BERT, with very few lines of code (though with a relatively long and computionally expensive trainning), and no data cleaning or feature enginerring whatsoever, we were able to train a model that perfomed better than 80% of the submissions of this Kaggle competition!

# TO DO:

Ideas to improve accuracy, without touching the base model:

- [ ]  Feature engineering

- [ ] Data cleaning 

- [ ] Change max lenght and batch size (must respect Max lenght * Batch Size < 3000 to not have OOM issues)

- [ ] Try to avoid over-fitting
