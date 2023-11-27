# Laptop Price Predictor
Machine learning model that predicts the price of laptops based on their specifications. This is a project in the Introduction to Machine Leaninrg course (CSC461)

# Project Description
You can find the instructions of this project in the ``` instructions.docx ``` file. It mainly consists of the steps below.

### Data Collection
> First of all, necessary libraries such as pandas, numpy, sklearn and many other were imported. The dataset is then loaded and you can access it in the ``` laptoppricing.csv ``` file. <br>
Overview of the dataset:
<img width="672" alt="image" src="https://github.com/Joe-Wehbe/laptop-price-predictor/assets/102875229/2d9e3e48-04f2-43dd-bcb8-1a5b7e2ee160">

### Data Preprocessing
> Many preprocessing steps were performed on the dataset including randomization, attribute datatype conversion, and variance inflation factor elimination. <br>
Dataset after preprocessing: <br>

<img width="309" alt="image" src="https://github.com/Joe-Wehbe/laptop-price-predictor/assets/102875229/8fc5b440-4ee3-4024-a052-490923d7fbf5">

### Model Training
> The model used is the Random Forest Regressor, which was trained on 80% of the dataset, and the remaining 20% was used for testing and evaluation. 

### Model evaluation
> After training, the model achieved an accuracy of 92.6% on the test set, however, it was improved using parameter tuning. 

### Parameter Tuning
> In order to improve the accuracy, grid search was performed to find the best regressor and estimators, which increased the accuracy of the model to 95.1%.

# How to run the project
## What to  download
Download the latest version of Python through this link:
```
https://www.python.org/downloads/
```
You can either download Anaconda and install jupyter from it through this link: 
``` 
https://www.anaconda.com/download
``` 
Or Download Jupyter with ``` pip ``` from your command line, follow this link for instructions:
```
https://jupyter.org/install 
```
If you downloaded the project with ``` pip ```, make sure to install the following libraries using the  commands below:
```
pip install pandas
pip install numpy
pip install seaborn
pip install matplotlib
pip install sklearn
pip install statsmodels
```

## Running the project
Download the project from my repository, navigate in Jupyter to the directory of the project, and open ``` LaptopPricePredictor.ipynb ```

# You're all Done!

