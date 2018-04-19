# Predicting Hurricane Trajectories Using an RNN
In this project, we use a recurrent neural network to predict the trajectory paths of hurricanes. We use the [Hurricane Database dataset from Unisys Weather](http://weather.unisys.com/hurricane/atlantic/). Here we preprocess the data, train a recurrent neural network on some of the samples, and compare our predictions against the real hurricanes. So far, we're using only the years 2000 to 2009 and is saved on our repo as '2000-2009-data.csv'. 

## Getting Started
The model was implemented using [Python 3.6](python.org/downloads). 
The code was written and run in a Jupyter notebook. For local installation, make sure you have [pip installed](https://pip.readthedocs.io/en/stable/installing/) and run: 
```
$ pip install notebook
```
Then to run, you would launch the notebook with:
```
$ jupyter notebook
```
### Main Tools Necessary
- [Keras](https://keras.io/models/model/)
- [TensorFlow](tensorflow.org)
- [NumPy](numpy.org)
- [Pandas](https://pandas.pydata.org/)

## Running 
The project successfully trains a model, however graphing the trajectories (latitude and longitude points) needs work. That graphing is under construction. 
