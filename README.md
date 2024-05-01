# Hybrid-Detection-Enhancing-Network-and-Server-Intrusion-Detection-using-Deep-Learning
Hybrid Detection Enhancing Network & Server Intrusion Detection using Deep Learning project for Final Project at Vardhaman College of Engineering.

This repository contains the sample code for the project "Hybrid Detection: Enhancing Network & Server Intrusion Detection using Deep Learning".

#Dataset Homepage: https://www.unb.ca/cic/datasets/ids-2017.html

#Outputs

1. Enhanced Network Detection
2. Hybrid Detection using XGB Classifier & MaxPooling 1D Modules
3. Benchmark Results for different ML and DL Models

|0 |BENIGN       |
|--|-------------|
|3 |DoS          |
|6 |WebAttack    |  
|1 |Bot          |   
|5 |PortScan     |
|2 |BruteForce   | 
|4 |Infiltration | 

#Performance Metrics achieved by the Ensemble Model for Each Label

| Label                             | Ensemble Model Accuracy  |
| --------------------------------- | ------------------------ |
| Benign                            | 99.83                    |
| Bot                               | 99.22                    |
| Brute Force                       | 100.0                    |
| DOS                               | 99.91                    |
| Infiltration                      | 85.71                    |
| Port Scan                         | 99.13                    |
| WebAttack                         | 99.88                    |

#Comparison of Different Classifiers

| Classifier	            |  Accuracy	  | Precision   |	Recall  |	F1-Score | Execution Time (s)  |
| ----------------------- | ----------- | ----------- | ------- | -------- | ------------------- | 
| Random Forest	          |  99.33%	    | 99.33%	    | 99.32%	| 99.33%	 | 4s                  |
| SVM	                    |  80.93%	    | 72.52%	    | 80.93%	| 75.66%	 | 110s                |
| KNN	                    |  97.53%  	  | 97.66%	    | 97.54%	| 97.58%	 | 2s                  |
| Decision Tree	          |   99.23%	  | 99.24%	    | 99.23%	| 99.24%	 | 1s                  |
| Gradient Boosting	      |  99.64%	    | 99.64%	    | 99.68%	| 99.56%	 | 118s                |
| Logistic Regression	    |  83.54%	    | 83.33%	    | 83.54%	| 83.14%	 | 7s                  |
| Light GBM	              |  99.71%	    | 99.68%	    | 99.71%	| 99.64%	 | 5s                  |
| Proposed Ensemble Model |  99.78%	    | 99.78%	    | 99.78%	| 99.78%	 | 39s                 |


