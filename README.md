# Steam Recommendation System: Based on Game Features and User Reviews

# Overview
This is a project for NUS BT5153 Applied Machine Learning for Business Analytics. Three models implemented in an attempt to
recommend games to users based on their reviews on Steam as well as the features of the games.

# Group 16
This project is done by:  
- Li Kangfu  
- Li Zhuoyi  
- Yu Ting 
- Zeng Xuran  
- Zheng Qingchuan  

# Library Packages
This project is implemented using Python 3. The following major packages are also needed.  
- NumPy
- Pandas  
- Gensium 
- NLTK
- Sklearn  
- Jieba  
- Keras  
- SciPy  
- Matplotlib  
- VaderSentiment  

# Dataset and Pre-processing
Because of the size of the datasets, we do not upload the original dataset, but only upload the processed datasets.
### Original Datasets
The original datasets can be downloaded from:
- ***steam_reviews.csv*:** Steam Reviews Dataset 2021, <https://www.kaggle.com/najzeko/steam-reviews-2021>
- ***steam_games.csv*:** Steam games complete dataset, <https://www.kaggle.com/trolukovich/steam-games-complete-dataset>

### Pre-processing
- Put the two datasets in the same directory as the Preprocessing.ipynb file
- Run the code (including cleaning, defining threshold and merging)
- Get ***steam_games.csv*** and ***steam_cleaned_less.csv*** (the only difference of the two files is that *steam_cleaned_less.csv* drops the columns which contains NA values)  
=== OR ===  
download the preprocessed dataset from this link https://1drv.ms/u/s!AsFAl5N0CEpEgZw52WtyCyXki5sjyw?e=yEpAPY

# How to Run
(1) Create a folder name *Cleaned data* in the same directory as the three ipython notebook file

(2) Put the two CSV files *steam_cleaned_less.csv* and *steam_games.csv* are inside the *Cleaned data* folder

(3) Run each file with Jupyter notebook
