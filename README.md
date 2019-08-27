# Soldier-Workload-Classification

In this project we are trying to classify the workload on various subjects using various non-linear algorithms. We are using the Electroencephalographical Recordings (EEG) of both, the subjects and then after feature 
extraction applying various non-linear classifiers to analyze the features.
      
We are implementing 5 deep learning algorithms - 
		  
	1. Artifical Neural Networks
	2. Support Vector Machines (SVMs)
	3. Stacked Autoencoders (SAEs)
	4. Radial Basic Function (RBFs)
	5. Linear Discriminant Analysis (LDAs) 
      
The accuracy of each model is calculated and the final classification is produced in terms of the 3 classes-
**Base Line (BL), Low Work Load (LWL) and High Work Load (HWL)**.  

The models designed, take the input as 14/64 channel data recordings and predict the outcome in form of these 3
classes. 

Furthermore, we are trying to analyze the affect of each individual feature of the signals (alpha, beta, etc)
on the final result and find out the correlation between these features.
The correlation is depicted using Pearson's correlation coefficient. 

The trained models will be capable of classifying the workload on any subject based 
on the EEG recordings and predict whether the user is having high, low or no workload. 