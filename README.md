# CRGANNC
The official code implementation for CRGANNC from our paper, Sub-clustering based recommendation system for stroke patient: Identification of a specific drug class  for a given patient.

## Model description

The full model architecture of our approach, CRGANNC (Clustering Recommendation Gaussian Affinity Nearest Neighbors Classifier), is outlined below. CRGANNC is a content-based recommendation model that utilizes three machine learning algorithms - Gaussian Mixture Model (GMM), Affinity Propagation (AP), and K-Nearest Neighbors (KNN) - to enable healthcare professionals (HCP) in timely detection of medications for stroke patients based on their symptoms.

Step 1. GMM dynamic clustering
Step 2. AF dynamic subclustering
Step 3. Generate K neighbors with KNN
Step 4. Calculate the representative rate for each drug among the k



