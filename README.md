Fake News Detection with Machine Learning & Search Integration

This project is a Fake News Detection system** built using Machine Learning and enhanced with a search engine integration to verify live news. It uses TF-IDF and Passive Aggressive Classifier to classify news articles as real or fake.

 Project Overview

- Goal: Automatically detect whether a news article is fake or real.
- Model: Trained on labeled fake and true news datasets.
- Extension: Integrated with [SerpAPI](https://serpapi.com) to search real-time news and classify it using the trained model.

Tech Stack

- Python
- Google Colab
- Pandas, NumPy, Matplotlib , Seaborn
- Scikit-learn
- SerpAPI (for live news search)

 Dataset

- [Fake.csv](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- [True.csv](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

Model

- TF-IDF Vectorizer: Converts text into numeric format.
- Passive Aggressive Classifier: Trains the model to classify news efficiently.

 Features

- Uploads news content from local or search engine.
- Predicts in real-time whether news is fake or real.
- Clean preprocessing and visualization included.

️ How to Run

1. Clone this repo or open the notebook in Google Colab.
2. Upload the datasets: 'Fake.csv' and 'True.csv'.
3. Install dependencies if running locally:
   bash
   pip install pandas numpy matplotlib seaborn scikit-learn
