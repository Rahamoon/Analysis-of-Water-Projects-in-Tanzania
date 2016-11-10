# Analysis of water projects in Tanzania
Competition hosted on drivendata.org

This repository contains IPython notebook code for the Pump it Up: Data Mining the Water Table competition on Driven Data.

[From Driven Data's competition details :](https://www.drivendata.org/competitions/7/)
The data is provided by Taarifa and the Tanzanian Ministry of Water. The goal is to predict which pumps are functional, which need some repairs, and which don't work at all...
A smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

![image](http://drivendata.materials.s3.amazonaws.com/pumps/pumping.jpg)

### Read the data

The first step is to read the data into pandas dataframes and join the training set and test set together. *(Reading the data.ipynb)*

### Clean the data and engineer features

The next step is to clean up the features (transform some, remove others) and possibly engineer some new features. *(Cleaning the data and engineering the features.ipynb)*

### Preprocess the data

Get the data ready for applying machine learning algorithms.*(Preprocessing the Data.ipynb)*

### Predict the operating condition of the waterpoints

Apply machine learning algorithms to predict which pumps are functional, which need some repairs, and which don't work at all. *(Modeling and predicting.ipynb)*

## Installation

### Download the data

* Clone this repo to your computer.
* Get into the folder using cd Pump it Up Data Mining the Water Table.
* Run mkdir data.
* Switch into the data directory using cd data.
* Sign up at [Driven Data](https://www.drivendata.org/competitions/7/page/23/) to download the following files:
    * Test set values.csv
    * Training set labels.csv
    * Training set values.csv

### Install the requirements

* Install the requirements using pip install -r requirements.txt.
    * Make sure you use Python 2.7.
    * You may want to use a virtual environment for this.

## Extending this

If you want to extend this work, here are a few places to start:
* Generate more features in Cleaning the data and engineering the features.ipynb.
* Switch algorithms in Modeling and predicting.ipynb.
