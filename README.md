![](Warren-Buffett.png)
# Predicting Cardano Stock Price

## Introduction

Cardano project is the home of the  Ada cryptocurrency, which can be used to send and receive digital funds. This digital cash as its CEO says represents the future of money, making possible fast, direct transfers that are guaranteed to be secure through the use of cryptography.

Cardano is more than just a cryptocurrency, however, it is a technological platform that will be capable of running financial applications currently used every day by individuals, organizations and governments all around the world.

Our data was obtained from Yahoo Finance and have all ADA stock prices from September 2017 to February 2020. Our goal is to predict the close price of a day based on the previous information.

## File Description

The dataset that we are going to work with is stored in ADA-USD-2.csv. This data set contains 861 rows with 6 variables.

We will use for our prediction Long Short Term Memory networks which are a special kind of RNN since the previous price of a stock is crucial in predicting its future price.

As we know the effectiveness of our trained neural network will depends on the weights that we used in our building process. Therefore, since we want that our results can be reproducible we  stored the trained model with the best performance in the file my_model.hdf5.

All the codes of our analysis are stored on the Jupyter Notebook Cardano.ipynb.
