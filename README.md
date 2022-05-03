# NLP for Recommendation Systems
This repository contains the code for our CS 7650 final project, titled "Anime Recommendation Systems using NLP Techniques".

All of the model implementations along with other discussed procedures from the paper are split among a few Jupyter notebooks (described below). The notebooks are "demonstration" ready and each notebook should be runnable end-to-end. But please make sure you first download the dataset and following the data processing steps below.

### Data Processing
1. Download the dataset from https://www.kaggle.com/datasets/marlesson/myanimelist-dataset-animes-profiles-reviews
2. Put the CSV files in `data/raw/`
3. Run the entire notebook `data_processing.ipynb` (should not take more than a few minutes), which filters our dataset and performs tokenization
4. Run the notebook `data_analysis_nlp.ipynb`, which computes and saves sentiment scores for each review

### Analysis
1. `data_processing.ipynb` and `data_analysis_nlp.ipynb` contain analysis of the dataset along with the preliminary sentiment score exploration. All the code used to generate the plots is contained in here as well.

### Models
1. `Basic_Matrix_Factoriztion.ipynb` contains the PyTorch model implementation and training code for the basic MF model, and `Sentiment_Matrix_Factorization.ipynb` contains the model implementation and training code for the Sentiment MF model.
2. ( #TODO: Nthistle add here)
