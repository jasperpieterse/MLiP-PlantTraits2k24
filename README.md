# PlantTraits2024

This repository contains the code for the **PlantTraits2024 Kaggle Competition**. We implemented deep learning models to classify six essential plant traits using **crowdsourced images** and **structured plant data**. More details about the competition can be found on the [Kaggle competition page](https://www.kaggle.com/competitions/planttraits2024).  

## Models  

We implemented five models to classify plant traits:  

1. **Swin Large Vision Transformer (ViT)** – A pre-trained vision transformer fine-tuned on plant images.  
2. **Regressor Model** – A simple regression model trained on tabular plant data.  
3. **LightGBM Model** – A gradient boosting model trained on tabular plant data.  
4. **Hybrid Model** – Combines features extracted from the ViT and tabular models, concatenating them and feeding them through fully connected layers.  
5. **Ensemble Model** – Combines predictions from an image-based model and a tabular model for improved accuracy.  

Each notebook details the **data preprocessing, model training, and inference process**. The attached report also outlines experiments, hyperparameter tuning, and insights gained throughout the project.  

## Installation  

These notebooks are designed to run in the **Kaggle environment** dedicated to this competition. To run the notebooks, follow these steps:

1. **Download the competition data** from the [Kaggle page](https://www.kaggle.com/competitions/planttraits2024).  
2. **Upload the notebooks** to the Kaggle environment.  
3. **Run the notebooks**

**Note:** For two of the models, training and inference are handled in separate notebooks. Be sure to follow the provided instructions in each notebook.  
