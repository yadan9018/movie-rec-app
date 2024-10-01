# movie-rec-app

## Description
I will attempt to build a movie recommendation app that suggests movies to users based on their preferences (e.g., genre, actors, etc.). I will use Python libraries such as pandas and scikit-learn to build the recommendation model. For the app interface, you can use Streamlit or Flask to create a web-based UI. It’s Good for practicing working with datasets, building recommendation models, and learning how to deploy your model into an app. This project is a good balance between learning AI fundamentals and building a functional app, making it an ideal beginner project you can complete in a month!

## Installation instructions
1. Install Python
Check if Python is installed: Open your terminal or command prompt and run:
  python --version   < If Python is not installed, download it from the official Python website and follow the installation instructions for your operating system. >

2. Install pip (Python Package Installer)
Check if pip is installed: Run the following command:
  pip --version < If it’s not installed, you can typically install it along with Python, or follow the instructions here. >

3. Set Up a Virtual Environment (Optional but Recommended) 
Create a virtual environment: Navigate to your project directory and run:
  python -m venv venv
Activate the virtual environment:
On Windows:
venv\Scripts\activate

4. Install Required Libraries
Once your virtual environment is active, you can install the necessary libraries using pip:
   pip install pandas scikit-learn streamlit flask
   
5. Verify Installation
You can verify that the libraries were installed correctly by running the following commands in the Python interpreter:
  python
  import pandas as pd
  import sklearn
  import streamlit as st
  import flask     < If you don’t encounter any errors, the installations were successful. >

6. (Optional) Install Jupyter Notebook
If you want to experiment with your data and visualizations interactively, consider installing Jupyter Notebook:
  pip install notebook
  jupyter notebook < to run jupyter >

Conclusion: Now your development environment is set up and ready to go! You can start exploring the MovieLens dataset and building your movie recommendation app.

## Download the MovieLens Dataset
1. Go to the MovieLens website : Choose the Dataset: For beginners, it’s recommended to download the smaller datasets, such as MovieLens 100K. Click on the link for the dataset you want (e.g., MovieLens 100K). 
2. Download the Dataset: You will usually be redirected to a page where you can download the dataset as a .zip file. Click on the download link to get the dataset. 
3. Extract the Files : After downloading, extract the .zip file to a directory on your computer. This will create a folder containing several .csv files (like u.data, u.item, u.genre, etc.).

## Recommendation System Approach
I plan to implement a **User-User Collaborative Filtering Model** to recommend movies. This approach will identify users with similar movie rating patterns and suggest movies that a similar user has liked but the current user has not seen yet. I will use cosine similarity to find users with shared preferences based on their past ratings. This technique will help provide personalized movie recommendations based on other users' viewing habits.






