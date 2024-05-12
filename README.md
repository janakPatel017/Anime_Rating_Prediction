# Anime_Rating_Prediction
Global Anime Market size was valued at USD 26.055 billion in 2021 and is poised to grow from USD 28.61 billion in 2022 to USD 60.06 billion by 2030, growing at a CAGR of 9.8% in the forecast period (2023-2030).
The focus of this post is to give you an idea of how we can explore data using graphs and gain valuable insights from the same.
Anime Market data includes company profiles, product images and specifications, capacity, production, price, cost, revenue, and contact information.
This market produces huge amount of data everyday on which data analysis can be performed to gain a greatest insight for an individual

# Problem Statement 
  The data-set aims to answer the following key questions:
  <b>Does various predicting factors really affect the rating of anime?</b>

# Challenges Faced:
  Some Features are hard to tackle and it was great challenge to work upon hyper parameters. 

# New Learning:
  Learned to make model using statsmodel and select features using Variance Inflation Factor and having Pvalue greater than 0.05 to drop those features
  * Industry standrad for VIF is 5 if it exceed the this value we are going to drop that Feature.
 
# Algorithm Used:
  * Linear Regression
  * Linear Regression Using StatsModel
  * Decision Tree Regressor
  * Random Forest Regressor

# Best R2 Score and Adjusted R2 score detected on decision tree Regressor Algorithm          
    Training       0.640(R2)   0.637(Adj.R2)
    
    Test           0.671(R2)   0.665(Adj.R2) 
    
    The Gap between training and test dataset is 3% so we are going to use this as final model.
