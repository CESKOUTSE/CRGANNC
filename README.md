# CRGANNC
The official code implementation for CRGANNC from our paper, Sub-clustering based recommendation system for stroke patient: Identification of a specific drug class  for a given patient.

## Model description

The full model architecture of our approach, CRGANNC (Clustering Recommendation Gaussian Affinity Nearest Neighbors Classifier), is outlined below. CRGANNC is a content-based recommendation model that utilizes three machine learning algorithms - Gaussian Mixture Model (GMM), Affinity Propagation (AP), and K-Nearest Neighbors (KNN) - to enable healthcare professionals (HCP) in timely detection of medications for stroke patients based on their symptoms.

#### Step 1. GMM dynamic clustering
#### Step 2. AF dynamic subclustering
#### Step 3. Generate K neighbors with KNN
#### Step 4. Calculate the representative rate for each drug among the k

![model_architecture](https://github.com/CESKOUTSE/dataset_for_recommend/assets/100790163/74f1e0ed-904d-44f0-9187-bd8659f5824a)

# Setup

First, clone this repository and move to the directory.


git@git


To run this code properly, you must update your Google Colab environment.

#### CRGANNC-model.ipynb: main code
#### data-engineering.ipynb: Data Engineering
#### GANs-augmentation.ipynb: TGAN data generation

# Dataset

#### dataset-stroke-data.csv: initial dataset
#### GAN_Stroke_Data.csv: dataset generated after TGAN
#### GAN_RECOMEND__Dataupdate6.csv: final dataset

# Citation

### RFT Ceskoutsé, AB Bomgni, DRG Zanfack, DDM Agany, TB Bouetou, EG Zohim Computers in Biology and Medicine, 2024•Elsevier

@article{ceskoutse2024sub,

    title={Sub-clustering based recommendation system for stroke patient: Identification of a specific drug class for a given patient},
  
    author={Ceskouts{\'e}, Ribot Fleury T and Bomgni, Alain Bertrand and Zanfack, David R Gnimpieba and Agany, Diing DM and Bouetou, Thomas Bouetou and Zohim, Etienne Gnimpieba},
  
    journal={Computers in Biology and Medicine},
  
    volume={171},
  
    pages={108117},
  
    year={2024},
  
    publisher={Elsevier}
    
}
