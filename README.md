# DrugInteraction


This code trains a drug target interaction model on the DAVIS dataset. It uses DeepPurpose model

To train the model, it splits the data into training and testing randomly. 

It also loads a pretrained model, and compares the mean squared error for the test data calculated from the newly trainied model vs the pretrained model 
