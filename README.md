# long-covid-classification

This repository contains our code, presentation, and write-up for our final project for EN.601.675 Machine Learning in Fall 2024.

Before running the code, the original data must be downloaded from the CDC here: https://www.cdc.gov/brfss/annual_data/2023/files/LLCP2023XPT.

More info here: https://www.cdc.gov/brfss/annual_data/annual_2023.html. The data is available to use from the CDC as public domain.

Running the notebook assumes that the .XPT data file is unzipped into the same directory as the notebook. Alternatively, the data can be uploaded to Google Drive and the lines referring to Google Drive in the notebook should be uncommented to run the notebook on Google Colab.

Running the notebook from start to finish will recreate our experiments described in the notebook and writeup.

Our Presentation: https://docs.google.com/presentation/d/13H7b1Rvtt-7xbSBa2TnNbZl5VBgsgCobczLfJ4cjrgw/edit?usp=sharing

Required libraries:
numpy
pandas
scikit-learn
xgboost
lightgbm
prince
