# Charity-Qualifiers

### Produced by:
* Arnold Schultz

# Overview:
This is a study to see if using a neural network model will produce a good prediction as to whether a charity is likely to succeed or not. If predictions are at least 75%, than we can use it's results to decide which charities will be awarded a donation.

## Tools used
Pandas:  Used to preprocess the data for use in Tensorflow

Tensorflow:  Used to create the prediction model

Keras-Tuner: Used to optimize the model used for prediction

sklearn: Used to convert the dataframe data into training and testing datasets

## Review

It seems no matter the parameters I change I cannot even get to 74%. I have tried several binning schemes as well as using keras tuner to try so many layer values, activations and epochs. I didn't want to rerun the tuner again due to time constraints. I tried dropping status column and it got worse, then I dropped income amount and it didn't really change. I then put them back. Last I tried changing the optimizer as well and it seemed adamax did slightly better.


## References


1. https://scikit-learn.org/ user guide for information on models/tools.
