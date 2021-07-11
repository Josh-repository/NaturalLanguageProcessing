# Review Text Analysis on Steam Online Gaming Platform Data using Naive-Bayes, SVM and kNN.

## Introduction 
These days every organization is keen on getting feedback from customers. Later, this data can be used for extracting some useful insights about the product developed, business plan, and so on. Manual extraction of such information is almost infeasible considering the amount of data extracted. Therefore, the review text analysis process uses machine learning algorithms to classify the feedback retrieved from each customer is either positive/1 or negative/0 based on some contextual parameters.  The principle goal here is to rightly classify the review text as much as possible. The report consists of three main parts. The first one was text data modeling where the encoding issue was addressed, the second one was text data preprocessing where the review text was preprocessed to better suit the final implementation part [i.e. machine learning model implementation]. Various ML models like Naïve-Bayes, Support Vector Machine [SGD], and kNearestNeighbors were implemented.  Later, I compared all three techniques with respect to an accuracy level of detecting the classification. I found that Naïve-Bayes performs better than SVM and kNearestNeighbors for the parameter whether or not to recommend the game and all three performs similarly for determining whether the review was for beta version or not.    

## Objective 
The main objective of this project is to determine whether machine learning models can be used to determine whether the review posted on to Steam Gaming platform website suggest • The game developed by this organization can be recommended or not. 
	• 	The review posted was for the beta version or the original release version of the game. 
 
## Implemenation:

1. Approach to Text Data Modelling. <br />	 
......... Import the Dataset <br /> 
......... Encoding/Decoding <br />
......... Converting Binary Text  <br />
......... Removing Smileys/Pictorial Text <br />
......... Language Conversion <br /> 
......... Export the dataset <br />

2. Approach to Text Data Preprocessing <br />
......... Overview  <br />
......... Import the Modified Dataset <br /> 
......... Basic Text Modelling and Cleaning Activities <br />
......... Feature Selection based on certain Characteristics <br />
......... Text Preprocessing Steps <br />
......... Data Splitting [Test/Train] <br />
......... Implementation [Machine Learning Algorithm] <br /> 
3. Baseline Model using dummy classifier <br />
4. Multinomial Naïve-Bayes model <br />
5. Linear SVM [Stochastic Gradient Decent] model  <br />
6. k-NearestNeighbors model  <br />
7. Performance Evaluation.

## Conclusion:

In this project, I successfully downloaded the raw dataset containing review text for Steam gaming platform and performed data cleaning activities, data preprocessing, implementation of machine learning algorithms like Multinomial Naïve-Bayes classifier, Linear Support vector Machine using SGD, K-NearestNeighbors and evaluated the performance using charts and graphs based on classification report, ‘ROC’ curve and ‘AUC’ value against baseline classifier. 