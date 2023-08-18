# Particulate Matter Composition Drives Differential Molecular and Morphological Responses in Lung Epithelial Cells

---
Paper: https://www.biorxiv.org/content/10.1101/2023.05.17.541204v1
Supplemental:https://drive.google.com/drive/folders/1RfR7b1sRLBWf17-iPg40dwAwgqx7qvGf?usp=drive_link

**Use Guide**:
1. **Manuscript and Figures Folder** 
   1. Contains paper and associated figures
2. **Notebooks Folder**
   1. Contains example workflow (use in conjunction with 'PM EXPOSURE DATASET' IN Supplement)
   2. *Preprocessing* delineates log normalization and standard scaling of morphological data
   3. *UMAP_KMEANS* describes 2D dimensionality reduction and identification of KMEANS clusters
   4. *Cluster of Clusters* describes identification of large cluster groups as described in the manuscript
3. **Supplementary Folder**
   1. Contains excel for dataset, models trained from the morphological analysis, and example cell profiler pipeline
   
---
**Python Library Dependencies**\
joblib==1.1.0\
pandas==1.5.2\
matplotlib==3.5.3\
numpy==1.22.4\
seaborn==0.12.0\
sklearn==1.0.2\
scipy==1.8.1\
umap==0.1.1
