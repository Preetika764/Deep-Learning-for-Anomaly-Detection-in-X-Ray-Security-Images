# Deep-Learning-for-Anomaly-Detection-in-X-Ray-Security-Images
This project was done as a part of the PS1 program at CEERI Pilani


The aim of this project is to recognize threat objects in x-ray security images.The dataset is highly biased towards one class (normal) due to insufficient images with 
abnormal data or anomalies. We are trying to recreate the results of the paper - ‘A New GAN-Based Anomaly Detection (GBAD) Approach for MultiThreat Object Classification on Large-Scale X-Ray Security Images’.

Dataset used - [https://github.com/MeioJane/SIXray]([url](https://github.com/MeioJane/SIXray))

We have attempted to recreate the results for the paper. Preprocessing is required to split the dataset using the annotations given for performing multilabel classification. We have used equal number of positive and negative images for Resnext50 to tackle the class imbalance problem. 

