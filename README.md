# Dog-Breed-Classifier
A CNN trained to determine the dog breed based on the face provided in an image.

## Project Overview

It's the Convolutional Neural Network(CNN) project in the Deep Learning Nanodegree program of Udacity. I learned how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, my algorithm identifies an estimate of the dog's breed. If supplied an image of a human, the code identifies the resembling dog breed.

## Project Instruction

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	```	
		git clone https://github.com/MeetPalod/Dog-Breed-Classifier
		cd Dog-breed-Classifier
	```
2. Open the `Dog-breed Classifier.ipynb` file.
	```
		jupyter notebook Dog-breed Classifier.ipynb
	```
3. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

4. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.
 
 
 ## (Optional) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.

## Project Information

### Contents

- Intro
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm
