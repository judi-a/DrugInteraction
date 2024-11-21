# DrugInteraction


The code written in DrugTargetInteractionPredictor shows how training a model for drug target interaction works. It trains a model on the DAVIS dataset. The DAVIS dataset contains a list of drug-protiens and their interaction scores. This work uses DeepPurpose model

To train the model, it splits the data into training and testing randomly. 

It also loads a pretrained model, and compares the mean squared error for the test data calculated from the newly trainied model vs the pretrained model 
