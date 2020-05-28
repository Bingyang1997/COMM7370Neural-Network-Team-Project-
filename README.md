# COMM7370Neural-Network-Team-Project-

It's our COMM7370 AI Theory and Applications group project at Hong Kong Baptist University.

# Where is China’s Used-car Market Headed?

## Team members:
- SONG Haoyu 19456190
- ZHOU Junjie  19447515
- CHU Bingyang 19456492
- ZHAO Bingjie 19454422
## Methodology
Out data comes from a machine learning competition. It has serval features such as amount of sales data, type of cars, province and quarter. We found that there is no text data in the data and most of features are numerical data. Besides, we need to predict the sales data. So, we decide to choose MLP as our base model. I use random function to separate the dataset. 80% training set and 20% testing set. I use L2 loss function as our loss function which can help machine learning get the learning progress. Besides, we don’t use dropout function in our net because the dataset is large and test results are not great even their train valid trend and test valid trend are fitting but their number are really high which means their prediction is bad. So, we need to start our experiment process to find out the best parameters.
MLP is an easy way to predict the sale data base on previous data. It is easy to understand the network structure and change parameters. Besides, L2 loss function is also can increase convergence rate. It can reduce the training time and speed the experiment process. However, MLP also is a simple machine learning model compare other famous machine learning model such as RNN, CNN or even other hybrid approach machine learning model. So, MLP’s performance maybe not the best result. Furthermore, when we change some parameters, their train loss and test loss are still high which means the model have some problems that can’t change by changing parameters. I believe that we may use wrong loss function because dataset may have some extreme data which will influence the result. L2 loss function can’t ignore extreme data while L1 loss function can optimize it. 
