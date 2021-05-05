# Image Classification for Dog Breeds
<img src="https://media1.s-nbcnews.com/i/newscms/2020_28/1587661/dogs-age-years-kb-inline-200707_7d0bca498155db9ae60dd81dec0ba6ab.jpg" alt= "dogs" >
Author: Anisha Malholtra

# Overview
This project applies Neural Networks to a dataset of dog images. In this project, each dog image is classified by its breed by training several models in efforts to determine the model with the highest accuracy score. 

# Business Problem
There are about 200 dog breeds in the world right now, which can make differing breeds from one another rather difficult. When dogs are rescued and taken to shelters, it can be benefical to determine which breed they are for medical reasons (certain breeds have different medical conditions) and so that they can find a forever home as fast as possible (if someone has a breed preference). Additionally, this classification system can also be useful to landlords who are renting out homes and only allow certain dog breeds.

# Data 
The data in this project was pulled from Kaggle and includes 20,580 images of 120 different dog breeds. The link to the data: https://www.kaggle.com/jessicali9530/stanford-dogs-dataset

<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/imagesbreed.png?raw=true" alt= "imagecount" >

There is no significant class imbalance issue, however it is evident that the breed with the most images are Maltese and least is Redbone.

# Model Evaluation

<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/eval.png?raw=true" alt= "eval" >

After running several models, the model with the highest accuracy score is the InceptionV3 Model with an accuracy score of 91.97%. Plotted below are the accuracy and loss per epoch graphs for this model.

<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/accuracy.png?raw=true" alt= "acc" >
<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/loss.png?raw=true" alt= "loss" >

# Predictions

Unseen images were passed to this model to test the accuracy of its predictions.

<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/lab.png?raw=true" alt= "lab" >
<img src="https://github.com/anisha732/DogImageClassification/blob/master/photos/shihtzu.png?raw=true" alt= "shihtzu" >

# Next Steps
- Include images of mixed breeds for the model to differentiate (ex: cockapoo, puggle)
- Create a recommendation system that recommends similar breeds based on input image
- Outputs characteristics of breed (ex: playful, intelligent, hypoallergenic, common medical issues, insurance liability)

# Repository Structure
```
├── photos
├── notebooks
├── Final_notebook.ipynb
├── DogClassificationPresentation
└── README.md
```


