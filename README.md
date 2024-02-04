# Topsis_Text_Classification
### Name: Pratyush Saxena
### Roll No: 102103302
### Group: 3CO11

##  Overview

Text classification involves automatically categorizing textual documents into predefined labels. The process begins with data preparation, where a labeled dataset is collected. Text preprocessing follows, cleaning and transforming the text into numerical features. A machine learning model is then selected and trained on the labeled dataset. I have used TOPSIS, or Technique for Order of Preference by Similarity to Ideal Solution. TOPSIS is a Multi-Criteria Decision-Making (MCDM) method that ranks options. The ideal solution is the best solution, which generally does not exist in practice.

## Models

I have selected the following 5 pre-trained models:

1. BERT

2. GPT-3

3. DistilBERT

4. RobBERTa

5. XLNet

## Library 

I have used my own topsis python package uploaded to PyPi to perform the topsis ananlysis on the data. To check out my package click [here](https://pypi.org/project/Topsis-Pratyush-102103302/)


## BARGRAPH

Bargraph showing TOPSIS Score vs Models

<image  width="600px" src="bargraph.png">

 ## Metrics

Table showing result of the TOPSIS package on output.csv

<image  width="600px" src="table.png">

##  TOPSIS Score Calculation
Utilized the custom 'Topsis-Pratyush-102103302' package to compute TOPSIS scores based on the model performance metrics.
[Link to Topsis-Pratyush-102103302 Package](https://pypi.org/project/Topsis-Pratyush-102103302/)


   <section id="evaluation-metrics">
        <h2>Evaluation Metrics</h2>
        <ul>
            <li>Accuracy</li>
            <li>ap</li>
            <li>F1 Score </li>
        </ul>
    </section>
    
 ## Analysis

GPT-3 has recieved **1st Rank** in this evaluation dataset. 
