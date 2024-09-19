## Bird Classification

## 1.Introduction
- There are so many species of birds and it can get really hard even for experts to tell which family a bird belongs to. Here machine learning model can make our task easy.
 
## 2.Objective
- In this project, we have 375 bird species and each species has around 150 images. Transfer learning is being used to initialize the weights. Resnet, VGG16, InceptionV3 and Xception pre-trained models are used. 

## 3.Steps to execute this Project.
- NOTE: Running the whole project might take an extended period of time. Training time also depends on your system's computation capabilities.
- 1.Download/fork/clone the project by clicking [here] (https://github.com/balusena/balugithub/tree/master/Bird_Species_Classification) or just unzip the folder provided.
- 2.src/ directory contains the notebook with data prep and modelling code. Put the training bird images in data/train/ and test images in the data/test/ directory.
- 3.In case you just want to see how the model is working, the model is provided in the models/ directory, load the model and go to the "Model Evaluation" section of the notebook and run the cells under that section.


## 4.Reports
- Report is available in the reports/ directory.

## 5.Plots
- Plots are available in the plots/ directory

## 6.Important Consideration
- This project runs perfectly on a windows machine by following the steps mentioned in section 3. If want to run on a different OS, encoding might need to be changed.

## 7.Further work to be done
- 1.Need to implement the classification using Random Forest, K-Nearest Neighbor (KNN) and Support Vector Machine (SVM) instead of VGG 16 and Resnet models and compare the results.
- 2.Planning to build a end-end web based bird classification application using the HTML, CSS, JAVA SCRIPT, Flask, or Strealit using Python and deploy it in Heroku, AWS Platforms. 
- 3.Find a way to measure how similar the classifications are with the current implementation (I would be grateful if someone could help me on this, in improving the model for better results).
