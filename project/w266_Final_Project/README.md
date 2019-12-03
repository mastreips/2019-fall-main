# W266 Natual Language Processing Final Project Git Repository

## Overview

This repository is in support of the final project submission for W266 Natural Language Processing as part of the Master of Information and Data Science Program at Univeristy of California, Berkeley. 
All inquiries regarding this repository may be directed to the corresponding author: mastreips@berkeley.edu

The project relies in part and is adapted from the following repositories:

- https://github.com/dmlc/dgl

- https://github.com/iamjagdeesh/Fake-News-Detection

- https://github.com/charles9n/bert-sklearn

- https://github.com/marcotcr/lime

- https://github.com/KaiDMML/FakeNewsNet/tree/old-version

The analysis for this project was done on both a Jupyter Notebook on Google Public Cloud and a Colaboratory Notebook:

## Setup and Method

### Data Preprocessing, BERT Embeddings (features), Edge List and Adjacency Matrix

On GCP n1-standard-1 (1 vCPU, 3.75 GB memory)

1) git clone https://github.com/iamjagdeesh/Fake-News-Detection (Preprocessing Script)

2) git clone https://github.com/KaiDMML/FakeNewsNet/tree/old-version (Data)

3) modify requirements.txt file with https://github.com/mastreips/2019-fall-main/blob/master/project/w266_Final_Project/BERT_GAT/requirements.txt to ensure the correct tensorflow version and extensions are installed (does not work with v.2.0)

4) replace files in codebase directory with those provided in /BERT_GAT/ directory (Customized Code)

5) run data processing code in Fake_News_GAT_analysis_v2 in jupyter notebook/lab 

### GAT Modeling

On GCP n1-standard-1 (1 vCPU, 3.75 GB memory)

1) git clone https://github.com/dmlc/dgl

2) Replace gotconv.py file from DGL directory for file in python pkg directory (dlg) (Customized Code)

3) run GAT modeling code in Fake_News_GAT_analysis_v2 in jupyter notebook/lab

### LIME Analysis of BERT Embeddings

On Google Colab 

1) run bert_lime_analysis.ipynb.  This will install the bert-sklearn wrapper and the lime libraries which are necessary to for the LIME analysis. 



