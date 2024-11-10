README.txt

# NLP Project: Sentiment Analysis on Rotten Tomatoes Dataset

##  Contributors
- Jden Goh
- Jovan Foo
- Shao Jie
- Qi Wei

## Overview
This repository explores sentiment analysis on the Rotten Tomatoes dataset using various neural network models (Simple RNN, CNN, BiLSTM, BiGRU, and an Ensemble model). Each model is trained and evaluated to determine the best-performing architecture for sentiment classification.

## Dataset
- The dataset used is the **Rotten Tomatoes** dataset, which can be loaded using the `datasets` library.
- The dataset is split into training, validation, and test sets.

## Setting up the Environemnt

Please download and unzip this folder.

### Create Virtual Environment

```bash
    python3 -m venv venv
```

### Activate your Virtual Environment
* On Windows:
```cmd
    venv\Scripts\activate
```
* On macOS and Linux:
```bash
    source venv/bin/activate
```
### Install Dependencies
The required dependencies can be installed  using the requirements.txt file provided.
```bash
    pip install -r requirements.txt
```

## Project Structure and Usage
* Train Models: Each model (Simple RNN, CNN, BiLSTM, BiGRU, Ensemble, etc) can be trained by running the corresponding cells in the notebook

* Evaluate Models: After training, each model is evaluated, and test accuracies printed and saved