## Recommendation-System-using-TensorRec-package

## 1.project
- In this project we are building Recommendation Engine in Retail Business using TensorRec module in Python, a deep-learning ML algorithm that uses Tensorflow and Keras backend with a rather simplified interface. In my opinion, it is user-friendly for beginners yet powerful and robust. Combining Pandas, Numpy, and SKLearn, together with TensorRec package module, we can harness the full potential of Python to produce a robust, solid, and relevant item recommendation. This project has used 1.Customer, 2.prod_cat_info, and 3.Transaction data. The transaction data (Transactions.csv) serves as a collaborative feature, because it describes the user’s (or customer’s) transaction-what and when they purchased, while the customer (Customer.csv) and product information (prod_cat_info.csv) serve as content features and item features respectively. We will refer the Transaction data as the master data, which we will append the relevant customer and product information from Customer.csv before we insert them into the Recomendation Engine. This project is build based on both content-based-recommendation and collaborative-filtering hybrid approach where both user similarity and item similarity altogether considered.

## 2.Objective
- The objective is to construct a recommendation engine to recommend relevant products to active customers (short-tailed) by filtering non-active customers (long-tailed) with high accuracy.

## 3.Plan
- The data that we have is from Retail Industry transaction, spanning from Jan 2011 to 2014. We will be creating a recommendation engine that recommends relevant products to users with high accuracy. TensorRec is used for building hybrid recommendation engine where it accepts only matrices so for that we will convert users, items, transaction features into matrix form where it standardize, normalize the data and speeds up the processes and saves a lot of memory.

## 4.Steps to execute this Project.
- NOTE:Running the whole project might take an extended period of time. Training time also depends on your system's computation capabilities.
- 1.Download/fork/clone the project by clicking [here] (https://github.com/balusena/balugithub/tree/master/Recommendation_Engine_TensorRec) or just unzip the folder provided.
- 2.src/ directory contains the notebook with data prep and modelling code.

## 5.Reports
- Report is available in the reports/ directory.

## 6.Plots
- Plots are availabel in the plots/ directory

## 7.Important Consideration
- This project runs perfectly fine on a windows machine by following the steps mentioned in section 3. If want to run on a different OS, encoding might need to be changed.

## 8.Further work to be done
- 1.Need to implement the retail recommendation implementing Market Basket Analysis using FPGrowth and Apriori algorithms, Cosine Similarity,KNN instead of TensorRec with k-means clustering for finding [R, M, F, V] feature market analysis and compare the results.
- 2.Planning to build a end-end web based retail recommendation application using the HTML, CSS, JAVA SCRIPT, Flask, or Strealit using Python and deploy it in Heroku, AWS Platforms. 
- 3.Find a way to measure how similar the recommentaions are with the current implementation (I would be grateful if someone could help me on this, in improving the model for better results).
