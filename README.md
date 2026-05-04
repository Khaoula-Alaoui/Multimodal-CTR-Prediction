# Multimodal CTR Prediction using Deep Learning

##  Overview
This project presents an end-to-end pipeline for Click-Through Rate (CTR) prediction using multimodal pretrained embeddings and deep neural networks.

The model integrates:
- User behavior features
- Item metadata
- Pretrained multimodal embeddings (provided in Task 1)

##  Model
We implemented a deep MLP architecture with:
- Embedding layers
- Feature concatenation
- Batch Normalization
- Dropout regularization

##  Results
- Baseline AUC: ~0.775
- Final Validation AUC: ~0.82
-  Competition Score: **0.832**

##  Key Insights
- Pretrained embeddings significantly improve performance
- Regularization is critical to control overfitting
- Simpler models (MLP) outperformed complex ones (Transformer, DIN)

##  Files
- `CTR_Prediction_Multimodal.ipynb` → main notebook
- `CTR_graphical_abstract.pdf` → project summary

##  Authors
- Aya Ismaili  
- Khawla Chrifi Alaoui  
- Rania Khaoudane  
