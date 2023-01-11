# General Information
In this project, an application has been made about decision trees. The purpose of using decision trees is to transform the complex structures in the dataset into simple decision structures. This is a generalizable definition for decision tree methods. In other words, it can be said that heterogeneous datasets are divided into homogeneous subgroups according to a determined target variable.  

There are bagging-based and boosting-based methods in decision trees.  

**Bagging**  

First of all, the concept of bootstrapping will be mentioned. Bootstrapping is random sampling with replacement from the training data. Bagging is the abbreviation of "Bootstrap Aggregation". It is the assembly of trees that have been created over and over again with the bootstrap method. The combined trees do not have any dependencies on each other. An important point is that a randomness occurs with bootsraping. This randomness makes bagged trees more powerful than single-tree models (CART etc.). Random Forest is the most popular bagging based machine learning algorithm.

**Boosting**

In boosting-based algorithms, new models are created by optimizing the created model. Each created model/classifier tries to increase its predictive power by compensating for the weaknesses of the previous models. Unlike the bagging methods, the trees created here are dependent on each other. There are several methods that are based on boosting. Examples of these are AdaBoost(Adaptive Boosting), GBM(Gradient Boosting Machines, XGBoost, LightGBM.These methods are based on the idea of ​​combining weak classifiers to create a strong classifier.  

![img](https://user-images.githubusercontent.com/78654212/211913815-01013e04-1d4d-4a25-b206-f0a2a553e817.JPG)
https://www.pluralsight.com/guides/ensemble-methods:-bagging-versus-boosting

**Advantages and Disadvantages of Bagging and Boosting**

**Advantages of Bagging**
* The biggest advantage of bagging is that multiple weak learners can work better than a single strong learner.  
* It provides stability and increases the machine learning algorithm’s accuracy that is used in statistical classification and regression.  
* It helps in reducing variance, i.e. it avoids overfitting.

**Disadvantages of Bagging**
* It may result in high bias if it is not modelled properly and thus may result in underfitting.  
* Since we must use multiple models, it becomes computationally expensive and may not be suitable in various use cases.

**Advantages of Boosting**
* It is one of the most successful techniques in solving the two-class classification problems.  
* It is good at handling the missing data.  

**Disadvantages of Boosting**
* Boosting is hard to implement in real-time due to the increased complexity of the algorithm.  
* The high flexibility of these techniques results in multiple numbers parameters that directly affect the behaviour of the model.  

The link of the website where information about the advantages and disadvantages of Bagging and Boosting methods is obtained is given below:
https://www.educba.com/bagging-and-boosting/  


# Business Problem and Dataset  

In this project, a machine learning model has been developed to predict house prices. In the dataset, there are various features of each house and the prices of the houses.  
