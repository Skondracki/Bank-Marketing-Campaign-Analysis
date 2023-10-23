# Bank-Marketing-Campaign-Analysis

## Project Description
The Bank Marketing Campaign Analysis project is the capstone project of an online data science course at BrainStation. Its primary objective is to predict whether clients will subscribe to a bank's term deposit product based on previous marketing campaign data. The project deals with data from direct marketing campaigns conducted by a Portuguese banking institution through phone calls. It is often necessary to have multiple contacts with the same client to determine if they subscribed ("yes") or did not subscribe ("no") to the term deposit.

## Dataset:

The dataset used can be found here [https://archive.ics.uci.edu/dataset/222/bank+marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing). While 4 datasets were created from the campaign tne subset bank-full.csv was used for this project.
 - bank-additional-full.csv: Contains all examples (41,188) and 20 input features, ordered by date.
 - bank-additional.csv: A subset of 10% of the examples (4,119) randomly selected from the full dataset.
 - bank-full.csv: Contains all examples and 17 input features, ordered by date (an older version of the dataset with fewer inputs).
 - bank.csv: A subset of 10% of the examples (4,119) randomly selected from the older dataset with fewer inputs.

The core objective is to predict whether a client will subscribe to a term deposit, represented by the binary target variable "subscribed."

## Why This Project?
The project is vital because it demonstrates the application of data science techniques in the banking sector, specifically in predicting customer behavior regarding subscribing to term deposit products. This predictive capability can significantly impact marketing strategies and campaign outcomes.

## How to Run the Code

1. Prerequisites:
   - Install Jupyter Notebook.
   - Make sure you have the required libraries installed: numpy, pandas, seaborn, matplotlib. You can install them using `!pip install library_name` within a Jupyter cell.

2. Download the Dataset:
   - Download the dataset 'full.csv' and place it in the same directory as your Jupyter Notebook file.

3. Opening the Jupyter Notebook:
   - Open a terminal or command prompt.
   - Navigate to the directory containing your Jupyter Notebook file and the dataset.
   - In the Jupyter Notebook interface, locate your notebook file and open it.
     
4. Executing the code:
   - Execute each code cell in sequence to load, preprocess, and analyze the data.
   - Use commented out code and analysis to help with your understanding of each code block.

## Features and Technologies

- Data preprocessing to clean and transform the dataset.
- Data exploration and visualization for insights.
- Implementation of logistic regression and decision tree models for prediction.
- Evaluation metrics such as accuracy, precision, recall, F1-score, R-squared (R2), and Mean Absolute Error (MAE).

## Project Credits 
This capstone project was developed by Sean Kondracki as part of an online data science course at BrainStation, taught by Arjun Sondh and Diya Abraham. 

## License
This project is licensed under the MIT License.
