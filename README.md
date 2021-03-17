# Machine Learning Using Python

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. **Machine learning focuses on the development of computer programs** that can access data and use it learn for themselves. <br>
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/machine-learning-definition.jpeg)<br><br>
## Repository Overview
This repository is about different Machine Learning algorithm approaches as per the industry practices.<br>

## Table of Contents
- [Gender Voice Recognition by Voice and Speech analysis](#section1)<br>
- [House Sale Price Calculation ](#section2)<br>
- [Market Basket Analysis on Groceries Data](#section3)<br>
- [Content based Recommendation system](#section4)<br>
- [HR attrition prediction using LDA dimensionality reduction](#section5)<br>
- [Telecom churn prediction using Deep learning](#section6)<br>

<a id=section1></a>
### [Gender Voice Recognition by Voice and Speech analysis](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/Gender%20Voice%20Recognition%20by%20Voice%20and%20Speech%20analysis)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/Speech%20Recognition.jpg)<br>
- Algorithm to understand and __classify__ if a person is male or female based on voice pattern
- This can be first step to further identify and develop an AI model for speech recognition 
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Gender%20Voice%20Recognition%20by%20Voice%20and%20Speech%20analysis/Gender%20Voice%20Recognition%20by%20Voice%20and%20Speech%20analysis.ipynb)

<a id=section2></a>
### [House Sale Price Calculation](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/House%20Sale%20Price%20Calculation)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/House%20Price.jpg)<br>
- __Sale Price of a house__ depends on a number of __features of the house__ ranging from the Plot area to the garage area.
- House Features can be both __qualitative as well as quantitative__. Thus requiring a deeper understanding of the data.
- An effort to build a model which can closely predict the price of the house.
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/House%20Sale%20Price%20Calculation/Machine%20Learning%20on%20House%20Sale%20Price.ipynb)


<a id=section3></a>
### [Market Basket analysis on Groceries Data](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/Market%20Basket%20analysis%20on%20Groceries%20Data)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/Groceries.jpg)<br>
- **Market Basket Analysis** is done by organizations so as to get itemsets that are frequent and regularly utilized together by customers. **Apriori algorithm** is a generally utilized system so as to discover those combinations of itemsets.
- It identifies parts which are often bought together and hence can be recommended to the user or be placed accordingly.
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Market%20Basket%20analysis%20on%20Groceries%20Data/Market%20Basket%20Analysis%20-%20Groceries%20Data.ipynb)


___
<a id=section4></a>
### [Content Based Recommendation System](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/Content%20Based%20Recommendation%20System)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/Recommendation%20Systems.jpg)<br>
- Content-based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback.
- TF-IDF (Term Frequency - Inverse Document Fequency is used in this example to calculate the frequency and find the cosine similarity between various items
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Content%20Based%20Recommendation%20System/Content%20Based%20Recommendation%20System.ipynb)


___
<a id=section5></a>
### [HR attrition prediction using LDA dimensionality reduction](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/HR%20Attrition%20prediction%20using%20LDA)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Images/HR%20management.png)<br>
- LDA is a dimensionality reduction technique but in a supevised dataset. Target variable has to be categorical.
- LDA can also be used to predict the target vaiable. 
- In the example various algorithms are compared with LDA as dimensionality reduction
- In this dataset of HR attrition, various features are used by HR to predict if an employee will leave the company or not.
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/HR%20Attrition%20prediction%20using%20LDA/Dimensionality%20Reduction%20using%20LDA%20and%20prediction%20using%20multiple%20algorithms.ipynb)


___
<a id=section6></a>
### [Telecom churn prediction using Deep learning](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/tree/main/Telecom%20churn%20prediction%20using%20Deep%20learning)
![enter image description here](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Telecom%20churn%20prediction%20using%20Deep%20learning/Telecom%20churn.png)<br>
- Telecom Customer Churn identification is a unique case study where we calculate if a user will churn or not based on various personal and usage details of the user with the company.

Deep Learning concepts used: 
- Dropouts: Dropout is a regularization method that tries to minimize the effect of ovefitting. Here particular node in a layer is randomly dropped out thus making a look alike layer with no dropped out nodes of the hidden layer. Nodes are dropped out randomly and allows algorithm to learn by giving opportunity to all nodes.
- Callbacks: Callbacks are methods called after execution of each epoch. They are primarily used to monitor the algorithm run and store necessary variables. Two callback functions used here are: Early stopping callback: This monitors the given variable to check if there is no change in the value of variable over a given time (patience) and asks the algortihm to stop processing further. This reduces the processing time. Model Checkpoint: Here the model with best monitor variable value is stored in a file which can be used later to get the best result.
- Regularization: To avoid overfitting, regularization is used to avoid algorithm to learn completely from the training data and have very low validation accuracy or high validation loss. Essentially system restricts blowing up of parameters during training the algorithm.
- [Link for the Jupyter notebook](https://github.com/anuragvyas1989/Python-Machine-Learning-Projects/blob/main/Telecom%20churn%20prediction%20using%20Deep%20learning/Telecom%20churn%20prediction%20using%20Keras%20API%20deep%20learning%20model.ipynb)
