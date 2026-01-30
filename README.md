# Merged Dataset and Explainable Transfer Learning for Indigenous Bangladeshi Fish Classification

## Abstract
Fish classification receives extensive global attention through deep learning approaches, yet studies specific to Bangladeshi species predominantly rely on limited, fragmented datasets with narrow diversity and controlled imaging conditions. This study aimed to bridge these gaps by developing a robust, interpretable framework and sought to establish a unified benchmark through dataset merging and advanced modeling.  

We merged two public datasets, **BengalDeltaFish** and the **Comprehensive Smartphone Dataset**, extracted 20 overlapping species to create the **MergeFishDataset** comprising 29,425 authentic images. We trained a baseline custom CNN on both individual and merged datasets before applying transfer learning with **MobileNetV2**, **InceptionV3**, **DenseNet121**, and **ResNet50** architectures.  

The merged dataset substantially outperformed individual ones:  
- Baseline CNN → 88.24% testing accuracy and 0.87 F1-score  
- Transfer Learning models → up to 98.8% accuracy and F1-scores  

Grad-CAM++ visualizations confirmed attention to biologically relevant features such as fins and body contours, complemented by **FLAN-T5-generated natural-language explanations**.  

This work establishes a large-scale, diverse, and interpretable benchmark for Bangladeshi fish classification, enhancing real-world generalization and promoting trustworthy applications in fisheries management and conservation.

---

## Dataset
The **MergeFishDataset** can be downloaded from Kaggle:  
[https://www.kaggle.com/datasets/mahadimhf/fishmargedataset](https://www.kaggle.com/datasets/mahadimhf/fishmargedataset)  

---

## Project Repository
GitHub repository:  
[https://github.com/Mahadi-Hasan402180/MergeFishDataset-Explainable-TL](https://github.com/Mahadi-Hasan402180/MergeFishDataset-Explainable-TL)  

---

## Project Structure


