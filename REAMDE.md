# Exploring the possibilities of music genre classification using MLP
> Timon Schneider  
> 03 November 2018

#### Abstract
In this project I will explore the possibilities to make a MLP classifier that predicts the genre of songs. With different preprocessing techniques and parameters of the MLP I am going to find out if the MLP net can do better than logistic regression. By that we would find if there are nonlinear relations that can be used in the classification. The data used is several preprocessed statistics from several rythm, chroma and mfcc bands. Ultimately I concluded that the data did not contain significant non-linear relations and a model like binomial regression suffices for this particular dataset.

#### Notes:
1) To run this code install keras, sklearn, pandas, numpy, tensorflow, imbalanced-learn and matplotlib
    - pip install -U imbalanced-learn
    - pip install keras
    - pip install tensorflow

2) Run this code only from top to bottom. If you run the code in a different order you have to run it all again from top to bottom.
