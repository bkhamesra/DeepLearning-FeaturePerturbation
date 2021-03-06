# Deep Learning - Feature Perturbation

With the emergence of deep learning, neural networks have found applications in almost every field ranging from financial analytics to computer vision and speech recognition. However, a common problem cited with this machine learning model is interpretability - due to multiple non-linear transformations, it is difficult to understand the final result and what characteristics of the initial data led to it. Feature perturbation can help in analysing the effects of individual features on the final results. This is a simple and extremely efficient method which can allow deep learning researchers to comprehend the black box neural networks by directly relating the changes in input features with the final output. Such a method can have wide applications in various domains ranging from credit monitoring, banking solutions, sales forecasting, risk management etc. Let’s consider a few examples.

### Loan Applications -
 Suppose a customer applies for a loan from a bank. The bank collects a range of information from your application and other services/vendors such as their financial and liquid assets, credit scores, credit history, number of defaulted payments etc and analyzes the data using machine learning models which rejects customer's loan application. The question of interest is what specific features in their application led to the rejection and what improvements are required to get the loan approved?

### Stock Prediction -
 The stock price of a company relies on several factors ranging from company portfolio, annual performance to daily trading exchanges. As a result the prices of stock varies continuously based on the changes in these factors. In order to make forecast, one needs to understand the impact of each feature on the final output. An alternate problem of higher interest for the traders and companies would be to understand which specific feature variations resulted in changes of stock price and if this can be quantified?

In this work, I consider a simple case of feed forward network with N hidden layers and develop the mathematical formalism to find the relation between perturbation of initial input and its effect on the final output. I first consider single feature perturbation and then extend the method to m features perturbation. To demonstrate, I consider a simple classifier to distinguish between positive and negative numbers and compute required changes in negative number to cross the zero boundary. 

## Content - 
* **FeaturePerturbation_Notes.pdf** - This file contains the mathematical formalism and final formulae used in the notebook. 
* **FeaturePerturbation.ipynb** - This is a jupyter notebook which demonstrates this method on a test case. 


## Using This Work - 
This work is currently under development and still not completely tested, so please use it at your own caution. I do not take any responsibility of use of this work or results obtained from it. I plan to improve this method, add further tests and some real world examples to demonstrate the applications of this method in future. If you enjoyed the project and would like to collaborate, please feel free to reach out. Also, if you wish to use it, please cite this repository. Thank you for checking out my work!
