# Tomato_Plant_Leaves_CNN

## Problem Statement
Farmers face economic loss and crop waste every year due to various diseases in potato plants. Common diseases are early blight and late blight. I used image classification using CNN that can be used to build an app that the farmer can use to detect these diseases early and apply appropriate treatment. This is done to prevent waste and economic loss.

## Dataset
[PlantVillage](https://www.kaggle.com/datasets/arjuntejaswi/plant-village) \
I kept only the tomato plant dataset.\

## Model
I built 3 models: 1. without a learning rate scheduler, 2. with a learning rate scheduler, and 3. with a learning rate scheduler and applied transfer learning using ResNet50V2.\
## Results 
__ Model 1 (model) __ \
accuracy: 0.80, loss: 13.1 \
__ Model 2(model_edited) __ \
accuracy: 0.79, loss: 5.02 \
__ Model 3 (model1) __ \
accuracy: 0.88, loss: 0.37 
