# InsectClassifier
## Project Description

This project uses a collection of insect images to train four different image classification models, then uses ensemble learning techniques to combine the predictions of these models. The entire project is conducted using Kaggle notebooks and the "CollectionOfInsectImages" dataset.

## Environment Setup

To set up your environment, you will need a Kaggle account. 

## Step 1: Training Individual Models

There are four notebooks used for training the individual image classification models. They are named as follows: 

- 'train_model-mobilenet.ipynb'
- 'train_model-xception.ipynb'
- 'train_model-densenet.ipynb'
- 'train_model-inceptionv3.ipynb'

To use these notebooks:

1. Create a new Kaggle notebook and upload the notebook.
2. Add the "CollectionOfInsectImages" dataset to the notebook.
3. Click on the "Run All" button to execute the code in the notebook.

Each notebook will train a model on the insect images dataset, and save a '.h5' file containing the trained model and a 'class_indices.npy' file containing the class indices. Save these files in a new directory.

## Step 2: Ensemble Learning

The ensemble learning approaches are implemented in the next two notebooks:

- 'approach1-soft-voting.ipynb'
- 'approach2-logisticregression-stacking.ipynb'

To use these notebooks:

1. Create a new Kaggle notebook and upload the notebook.
2. Add the "CollectionOfInsectImages" dataset to the notebook.
3. Add the directory of trained models.
4. Check filepaths.
5. Click on the "Run All" button to execute the code in the notebook.

## Step 3: Results

Each notebook will report its individual results.
