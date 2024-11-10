README.txt

# Project: Sentiment Analysis on Rotten Tomatoes Dataset

## Overview
This Jupyter notebook explores sentiment analysis on the Rotten Tomatoes dataset using natural language processing (NLP) techniques. The project includes data preprocessing, feature extraction using Word2Vec, and building a classification model using PyTorch.

## Dataset
- The dataset used is the **Rotten Tomatoes** dataset, which can be loaded using the `datasets` library.
- The dataset is split into training, validation, and test sets.

## Libraries and Dependencies
The following Python libraries are required to run the notebook:
- `datasets`
- `nltk`
- `numpy`
- `gensim`
- `torch`
- `kagglehub`
- `pandas`
- `requests`
- `tqdm`
- `aiohttp`

Make sure to install the necessary packages before running the notebook. You can install them using:
'''bash
pip install datasets nltk numpy gensim torch pandas requests tqdm aiohttp
'''

Preprocessing
- Stopwords: The nltk library is used to download and utilize stopwords for text preprocessing.
- Word Embeddings: The gensim library is utilized to train Word2Vec embeddings on the dataset.

Instructions to Run
1. Ensure that Python 3 and Jupyter Notebook are installed on your system.
2. Install the necessary dependencies using the command provided above.
3. Open the notebook using Jupyter:
'''bash
jupyter notebook Another_copy_of_SC4002_1.ipynb

4. Execute the cells sequentially to preprocess the data, train the model, and evaluate its performance.

Hardware Requirements
If available, the notebook is optimized to run on a GPU for faster training (torch.device("cuda" if torch.cuda.is_available() else "CPU")).

Author
Jovan Foo, Jden Goh, Lim Shao Jie, Ng Qi Wei

---

Let me know if you'd like to adjust any sections or add further details!
