# ECG Capstone Project


---

````markdown
# ECG-Based Classification using Deep Learning

##  Capstone Project - ML for Healthcare

This project compares two deep learning models with a traditional machine learning baseline for classifying ECG signals using the ECG5000 dataset. It includes:

-  Method A: ResNet-Inspired 1D CNN  
-  Method B: Lightweight CNN Benchmark  
-  Method C: K-Nearest Neighbors (baseline)  

##  Files

- `method-a-ResNet-Inspired Model.ipynb` – Deep learning using ResNet-style residual blocks  
- `Method-B-CNN-Benchmark-Model.ipynb` – Lightweight CNN inspired by PTB-XL benchmark  
- `KNN-from-capstone-part-1.ipynb` – Classical KNN classifier  
- `ECG5000_train.pickle` & `ECG5000_validation.pickle` – Preprocessed datasets  

## Results Summary

| Model     | Accuracy | F1 Score | AUROC  |
|-----------|----------|----------|--------|
| KNN   | 0.922    | 0.911    | 0.9611 |
| CNN   | 0.872    | 0.834    | 0.9502 |
| ResNet| 0.891    | 0.851    | 0.9656 |

##  Requirements

```bash
pip install numpy pandas scikit-learn torch matplotlib
````

## Summary

This project demonstrates that simpler models like KNN may outperform deep learning in low-data, structured signal environments. However, deep networks show stronger potential in generalization and minority class detection.




