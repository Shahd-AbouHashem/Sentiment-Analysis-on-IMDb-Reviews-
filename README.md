# Natural Language Processing Program Task 1 Level 1 
### Elevvo pathways tech intern

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)

Analyze product reviews to classify sentiment as positive/negative using:
- Logistic Regression
- Naive Bayes classifiers

## Features
✅ Text preprocessing (lowercasing, stopword removal, lemmatization)  
✅ TF-IDF vectorization  
✅ Model training with hyperparameter tuning  
✅ Visualization of key words  
✅ Performance comparison 

### Dataset
[Download from Kaggle and place in data/raw/](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

#### `.gitignore`

Data files
data/raw/
*.csv

Models
models/*.pkl

IDE
.idea/
pycache/

#### `requirements.txt`

nltk==3.7

scikit-learn==1.0.2

pandas==1.4.2

matplotlib==3.5.1

seaborn==0.11.2

wordcloud==1.8.1

joblib==1.1.0
