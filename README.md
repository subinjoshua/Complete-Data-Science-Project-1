##### The objective of this project:
- Simple Version:
  * To finally create a model that can predict if the customer will dispute the solution given by the company
  * It is to analyse the data, make intelligent models that are capable of predicting certain feature(s) and then pitting these best selected model(s) against actual data to see how it works
- Long Version:
  * Part 1 is all about Data Exploration. Here we try and gain information of the data and clean the data that we are using,these questions are answered:
    1. What is the data about?
    2. What columns are related and inwhat manner?
    3. Questions about the data(domain related questions)[These are the sub-headings]
    4. How can I visualize these data to understand/present it better?
  * Part 2 is me trying to making a model that can predict the product from the customer's complaint narrative
    1. I create a text classifier which is capable to correctly predictiing the product from just the customer's narrative
    2. Used TDIDF and complex data cleaning techniques  
  * Part 3 is creating a model that can successfully predict our objective
    1. Used grid search to tune hypermaters
    2. Selected features that are meaningful to the prediction model
    3. Explored cross-validation to give a more robust validation
    4. Used RandomForestClassifier
    
