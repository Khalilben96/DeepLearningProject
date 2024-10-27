Overview

This is a project related to the classification of images of animals using deep learning techniques.
It will show how one can develop a model for predicting the species of animals in images from their visual features.
First, train the model on a labeled dataset and then check its performance with different metrics.
This would also include visualizations of the model's predictions by showing correctly and incorrectly classified images.

Requirements

To ensure that the project runs smoothly, the following Python packages are required:

    scipy: 1.9.3
    matplotlib: 3.9.2
    numpy: 1.25.2
    pandas: 2.2.3
    seaborn: 0.13.2
    tensorflow: 2.10.1
	
	
Implementation Steps

Image Preprocessing: Images are loaded, resized, and normalized for use in the model.
Model Training: A deep learning model is built and trained on the training dataset. The model's performance is validated using a separate validation dataset.
Evaluation: Various metrics such as precision, recall, F1 score, and support are calculated to evaluate the model's performance.
Visualization: The model's predictions are visualized, showing both correctly and incorrectly classified images.	

Dataset

The dataset used for this project is the Animals-10 dataset, which contains images of various animal species. You can download the dataset from Kaggle using the following link:

    https://www.kaggle.com/datasets/alessiocorrado99/animals10

The dataset includes images for the following animal classes:

    Cane (Dog)
    Cavallo (Horse)
    Elefante (Elephant)
    Farfalla (Butterfly)
    Gallina (Hen)
    Gatto (Cat)
    Mucca (Cow)
    Pecora (Sheep)
    Ragno (Spider)
    Scoiattolo (Squirrel)
