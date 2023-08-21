# Portfolio
This is a summary of primary repositories.

## Machine Learning
### Design Service User Prediction
#### https://github.com/feifangu/Design-Service
Part 1: EDA - Load the dataset and take a quick look <br>
Part 2: Data Cleaning - Replace na with unknown for categorical variables and with zero for numerical variables <br>
Part 3: Data Visualization - Visualize the X variables and y variable and notice the imbalancement of y <br>
Part 4: Feature Engineering - Split dataset into training (to train the model) and test sets (to test the model); one hot encoding on categorical variables; Upsample with SMOTE and downsample with random sampling the datasets to get prepared for different models <br>
Part 5: Modeling - Compare different classification models on their performance (f1, ROC_AUC, accuracy, training time); pick the best one and do grid search with cross validation to tune hyper parameters to optimize <br>
Part 6: Summary - Business strategy recommendation <br>

### Learning Notes of Approaching (Almost) Any Machine Learning Problem
#### https://github.com/feifangu/AAAMLP-Notes
Documenting down the code and key takeaways of learning the book.

### Click-through Prediction
#### https://github.com/feifangu/click-prediction
This project involves predicting clicks for on-line advertisements. The training data consists of data for 9 days from October 21, 2014 to October 29, 2014. Our goal is to predict the probability of a click. The performance criterion used to evaluate the performance of prediction is log-loss. I operated various classification algorithms to pursue a lower log-loss including LightGBM and XGBoost.

## Marketing Analytics
### Clustering and Recommender System
#### https://github.com/feifangu/Marketing-Analytics
This project aims to help Pernalonga, our client to develop a marketing campaign focusing on Shampoo and Hair Conditioner categories to experiment on personalized promotions. Clustering and recommender systems are leveraged to establish a most profitable personalized campaign with which we estimated to achieve $80,000 profits considering halo effect with $4,000 cost in redeemed discount.

## Data Visualization
### User Network Visualization
#### https://github.com/feifangu/meetup-data-visualization
A Tableau strory cosisting of 4 dashboards to explore the use of Meetup.com, including using R (data.table and igraph) to do social network analysis between users and groups of Meetup. The Tableau ended as a practical tool for a user to track popular categories, groups and events.
 
## Social Network Analytics
### Start-up Strategy Analytics
#### https://github.com/feifangu/social-network-analysis
I analyzed how the co-investment networks of venture capital firms influence their strategies, in terms of the types of startup companies that they invest in. I also explored the relationship of investors' status, their diversification and the chance of successful investment; I analyzed the impact of failing fast through homophily on startups. The projects involves network analysis in R involving packages usage such as igraph, nnet, etc..
