# Detecting Fake News Project
Do you trust all the news you hear from social media?

All news are not real, right?

How will you detect fake news?

In this project we're going to detect fake news with python and machine learning by do some natural language processing to our data and using `sklearn` to build a model to accurately classify a piece of news as REAL or FAKE.

## Result
We've reached 93,84% accuracy with SGDClassifier to predict whether the news is Fake or Real.

Confusion matrix:

<img src= ./conf-matrix.png width=300 >

## Setup
0.Install Anaconda or Miniconda [here](https://docs.anaconda.com/anaconda/install/)
 
1.Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/VincentJonathanz/predicting-fake-news.git
```
2.Create and activate enviroment.
   - **Anaconda Prompt**:
      ```
      conda env create --prefix ./env -f enviroment.yml
      conda activate predicting-fake-news/env
      ```
      
   - **Powershell** (you need to run this command first then run the command above):
      ```
      conda init powershell
      Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
      ```
      
3.Start Jupyter
``` 
jupyter notebook
```
