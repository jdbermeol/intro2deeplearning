# Introduction to Deep Learning

## Topics Covered
* Introduction to Neural Networks and Deep Learning
* Building a simple neural network from first principles
* Introduction to Backpropagation algorithm
* Multi-layer perceptron
* Convolution Neural Networks
   *  Introduction to Convolution
   *  Image Recognition using CNN
* Natural Language Processing :
   *  Introduction to `word2vec`
   *  Introduction to Recurrent Neural Networks
   *  Text classification using RNN
   *  Text generation using RNN
*  Unsupervised learning using Autoencoders

*Depending on time, some of the topics may not be covered during the workshop. But, please note that the entire content(data and source code in `ipython notebook` format) would be available in this repository.*


## Slides for the workshop
https://speakerdeck.com/bargava/introduction-to-deep-learning

## Setup Guide
*Pre-requisites: git, python 2.7.X, virtualenv, pip (7.1.X recommended)* 

* Here are all the packages you'll need before you can
  proceed

  ```
  $ python -m pip install --upgrade pip
  $ python -m pip install --upgrade virtualenv
  ```

* Clone the repo from GitHub

    ```
    $ git clone https://github.com/jdbermeol/intro2deeplearning.git
    $ cd intro2deeplearning
    ```

* Create python virtual environment
    ```    
    $ virtualenv env
    $ source env/bin/activate
    ```    

* Install requirements using pip

    ```
    $ python -m pip install -r requirements.txt
    ```

* When the requirements are being downloaded / installed, Fetch the datasets
  simultaneously

    ```
    $ sh download_data.sh
    ```
* Run the notebook
    
    ```
    $ cd notebooks
    $ KERAS_BACKEND=theano jupyter notebook
    ```
    This opens your default browser which displays the list of notebooks in the
    current directory. 
    
    Open **1. Introduction to Artificial Neural Networks.ipynb**.
    Now, run the first cell with imports in the notebook (shift + enter).
    If you have all the dependencies installed, this should run without any
    errors.
