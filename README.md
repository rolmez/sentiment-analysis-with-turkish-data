# Sentiment Analysis with Turkish Data
This project includes a study on **Sentiment Analysis**. Comparison of sentiment analysis machine learning models created by trying various methods such as **BoW, TF-IDF** with the data I collected using **Twitter**.

**Dataset:** I obtained the dataset using Tweepy and Twint and scraped tweets with a specific keyword. The dataset is divided into positive and negative comments. I labeled the data individually and applied various word representation techniques by preprocessing the data such as removing special characters, removing numbers, etc.

**Models:** Logistic Regression, Naive Bayes, SGD

## Contents of the PDF
- Introduction
  - Purpose of the Thesis
  - Literature Research
- Scientific Background
   - Natural Language Processing
   - Sentiment Analysis
   - Machine Learning
- Methodology
   - Dataset
   - Labeling of Data
   - Preprocessing
   - Finding Word Roots
   - Attribute Representation
- Success
   - Success Criteria
- Conclusion and Evaluation
   - Model Application
   - Conclusion
   - Discussion

## Usage

```bash
git clone https://github.com/rolmez/sentiment-analysis-with-turkish-data.git

cd sentiment-analysis-with-turkish-data

pip install -r requirements.txt

jupyter notebook sentiment-analysis.ipynb
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
