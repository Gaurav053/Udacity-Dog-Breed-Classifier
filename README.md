[//]: # "Image References"

[image1]: ./images/sample_dog_output.png "Sample Output - Dog"
[image2]: ./images/sample_human_output.png "Sample Output - Human"
[image3]: ./images/sample_cnn "VGG16 Model Figure"

# Dog Breed Classifier Capstone Project

## Project Overview

This project aim to build a ML pipeline to identify the dog breed from a dog image and identify the resembling dog breed if human images are suplied as input. This pipeline can be used in web-app or mobile app to provide interative experience to End Users.

![Sample Output - Dog][image1]  
![Sample Ouput - Human][image2]

Refer to Project Proposal and Report for better understanding of the use-case and implementation in detail.

## Dependencies

This project mainly makes use of Python, Jupyter Notebooks, OpenCV and PyTorch. Other packages used in this project have been listed in the `requirements.txt` . Please follow the instructions provide below for installation.

## Project Instructions

To manually run through the code locally, follow below instructions.

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/Gaurav053/Udacity-Dog-Breed-Classifier.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
   
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`. 

4. Install the necessary Python packages

   ```
   pip install -r requirements.txt
   ```

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

  ```
  jupyter notebook dog_app.ipynb
  ```
