# Trip Advisor Hotel Reviews
Hotels play a crucial role in traveling and with the increased access to information new pathways of selecting the best ones emerged.

With this dataset, consisting of 20k reviews crawled from Tripadvisor, you can explore what makes a great hotel and maybe even use this model in your travels!

## 1. Problem

We are provided with this dataset, consisting of **20k** reviews crawled from Tripadvisor. Each review has its corresponding rating ***(1-5)***. The goal is to develop a Sequence model capable of classifying the reviews but into **3** classes instead of **5**. 

## 2. Data

The data we're using is from Kaggle's Trip Advisor Hotel Reviews dataset.

https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews

## 3. Evaluation

We will evaluate the model based on the accuracy metric, making sure that it doesn't have **High Variance** or **High Bias**.


## 4. Features
* There are 5 ratings ***1*** to ***5*** which we will have to change to 3 classes ***Bad, Good, and Neutral 1 to 3***.
* There are around ***20k*** reviews which we will split into training and testing.
