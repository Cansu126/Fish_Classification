                                Fish Species Classification Project

Project Purpose: The aim of this project is to develop a deep learning model that can accurately classify fish species. The model takes fish images as input and determines which species these images belong to.                                

Dataset: In the project, the "A Large Scale Fish Dataset" dataset on the Kaggle platform was used. This dataset contains images of 9 different fish species.

These fish species:
•Hourse Mackerel
•Black Sea Sprat
•Sea Bass
•Red Mullet
•Trout
•Striped Red Mullet
•Shrimp
•Gilt-Head Bream
•Red Sea Bream

Used libraries:
•Pandas: Used for data processing and manipulation.
•Matplotlib & Seaborn: Used for visualization and data analysis.
•NumPy: Used for matrix and array operations.
•TensorFlow & Keras: Used to create deep learning models.

Code Structure: The code consists of the following steps;
1. Importing Modules : Introducing the necessary participation into the project.
2. Data Set Upload : Writing the data set consisting of pictures of fish species.
3. Data Set Review : Analysis of the data set.
4. Data Preprocessing : Preprocessing the data setting, making it suitable for training
5. Modeling : Architecture of the model and training of the Model.
6. Model Performance and Evaluation Metrics : Graphical evaluation.
7. Class Predictions on Test Data : Class predictions of the model

   
Model Structure
Main layers used:
•Dense (Dense Layer): Fully connected layers.
•Flatten: Flattens the data.
•Dropout: Prevents overlearning.
•BatchNormalization: Normalizes layer outputs during training.
    Adam optimization algorithm was used.The model uses Sequential Model architecture.


Model Performance
Test loss: 0.3259062170982361
Test accuracy: 0.9077777862548828
These results show that the model performs well on the training data and is consistent on the validation set.

Kaggle: https://www.kaggle.com/code/cansuevik/fish-classification-deep-learning

    
