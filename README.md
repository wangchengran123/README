# Dog-Breed-Classifier: CNN Project [Udacity Deep Learning Nanodegree]

## Project Overview

This is the Convolutional Neural Networks (CNN) project for Udacity Machine Learning Nanodegree. The aim of this project is to learn to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the algorithm used will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

The main steps:
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dogs
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Algorithm
- Step 6: Test Algorithm

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
    
__NOTE:__ if you are using the Udacity workspace, you *DO NOT* need to re-download the datasets in steps 2 and 3 - they can be found in the `/data` folder as noted within the workspace Jupyter notebook.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```
## Method adopted
ResNet

## Result:
Above 80% accuracy

## References：
[1] https://en.wikipedia.org/wiki/Dog_breed
[2] Chanvichitkul, Massinee, Pinit Kumhom, and Kosin Chamnongthai. "Face recognition based dog breed classification using coarse-to-fine concept and PCA." 2007 Asia-Pacific Conference on Communications. IEEE, 2007.
[3] Borwarnginn, Punyanuch, et al. "Breakthrough Conventional Based Approach for Dog Breed Classification Using CNN with Transfer Learning." 2019 11th International Conference on Information Technology and Electrical Engineering (ICITEE). IEEE, 2019.
[4] https://heartbeat.fritz.ai/a-beginners-guide-to-convolutional-neural-networks-cnn-cf26c5ee17ed
[5] https://github.com/udacity/dog-project
