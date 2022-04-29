# **MACHINE LEARNING** IS ABOUT **DATA DRIVEN DECISION MAKING**
It has two parts ;
- TRAINING
- PREDICTION

Machine learning is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention. It works as ;
- Data
- Learning / training
- Model 
- Prediction
- Decision
Its goal and usage is to build new and/or leverage existing algorithms to learn from data, in order to build generalizable models that give accurate predictions, or to find patterns, particularly with new and unseen similar data.

> There are four types of machine learning algorithms: 
- **SUPERVISED**
  - It is defined by its use of labeled datasets to train algorithms that to classify data or predict outcomes accurately. As input data is fed into the model, it adjusts its weights until the model has been fitted appropriately, which occurs as part of the cross validation process.
  - Supervised learning helps organizations solve for a variety of real-world problems at scale, such as classifying spam in a separate folder from your inbox.
- **SEMI-SUPERVISED**
  -  is an approach to machine learning that combines a small amount of labeled data with a large amount of unlabeled data during training.
  -  Semi-supervised learning falls between unsupervised learning (with no labeled training data) and supervised learning (with only labeled training data).
  -  It is a special instance of weak supervision.
- **UNSUPERVISED**
  - is a machine learning technique in which the users do not need to supervise the model. Instead, it allows the model to work on its own to discover patterns and information that was previously undetected. It mainly deals with the unlabelled data.
  - Unsupervised learning algorithms include clustering (K-means clustering,probabilictic clustering,
  - hieratical clustring), anomaly detection, neural networks, etc.
- **REINFORSEMENT**
  - There is no supervisor, only a real number or reward signal
  - Sequential decision making
  - time plays a crucial role in Reinforcement problems
  - Feedback is always delayed, not instantaneous
  - Agent’s actions determine the subsequent data it receives
  - Two types of reinforcement learning are 
    - 1) Positive 
    - 2) Negative
  - Two widely used learning model are 
    - 1) Markov Decision Process 
    - 2) Q learning

## **SUPERVISED**

- Supervised learning uses a training set to teach models to yield the desired output. This training dataset includes inputs and correct outputs, which allow the model to learn over time. The algorithm measures its accuracy through the loss function, adjusting until the error has been sufficiently minimized.

- Supervised learning can be separated into two types of problems when data mining—classification and regression:

### **CLASSIFICATION**

- uses an algorithm to accurately assign test data into specific **categories**. 
- It recognizes specific entities within the dataset and attempts to draw some conclusions on how those entities should be labeled or defined. 
- Common classification algorithms are linear classifiers, support vector machines (SVM), decision trees, k-nearest neighbor, and random forest, which are described in more detail below.

- **Regression** is used to understand the relationship between dependent and independent **numeric** variables. It is commonly used to make projections, such as for sales revenue for a given business. Linear regression, logistical regression, and polynomial regression are popular regression algorithms.