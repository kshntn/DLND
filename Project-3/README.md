# TV Script Generator

## Project Overview

In this project, I generated my own [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) TV scripts using RNNs. I used part of the [Seinfled dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons. The Neural Network generated a new, "fake" TV script, based on patterns it recognizes in this training data.


### Contents
* Get the Data
* Explore the Data
* Implement Pre-processing Functions
	* Lookup Table
	* Tokenize Punctuation
* Pre-process all the data and save it
* Check Access to GPU
* Input
	* Batching
	* Test your dataloader
	* Sizes
	* Values
* Build the Neural Network
	* Define forward and backpropagation
* Neural Network Training
	* Train Loop
	* Hyperparameters
	* Train
* Generate TV Script
	* Generate text
	* Generate a new script
