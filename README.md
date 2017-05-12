# Network Intrusion Detection

Algorithms like Naive-Bayes, Decision trees and Random Forests are designed and implemented over the data set of NSL-KDD.
A complete visualization of attributes and also the output of algorithms is given. The entire process of training and classification is split up in modules so that it is easy for the developer to understand.

## Description of the data set

**NSL-KDD** data set is a refined version of its predecessor which is KDD cup 99 from DARPA. In each record there are 41 attributes unfolding different features of the flow and a label assigned to each either as an attack type or as normal. These 41 attributes are divided into 4 groups:
- **Basic features**
- **Content related**
- **Time related features**
- **Host based traffic features:**

The entire data and description can be found here: [click here](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

## Classification of attacks

 The 4 main classes of attacks are: 
 - **Denial of service (DoS)**
 - **User to root (U2R)**
 - **Remote to user (R2L)**
 - **Probing** 
 
 ## Pre-processing and attribute selection
 
The attribute selection is the tricky part. Typical models like random forests, decision trees, etc take very long time to build the model. Hence, the number of attributes must be reduced. Moreover, there are many zero variance features which are removed in this step.   
  
## Classifier build

- **Naive Bayes**
- **Decision Trees**
- **Random Forests**