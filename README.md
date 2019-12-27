# -M3DV-
This is the course assignment of EE369 machine learning 2019 autumn course of Shanghai Jiaotong University, 3D medical image classification (M3DV) Kaggle inclass competition.
This is a classification project of pulmonary nodules. We use a deep learning system to complete this project, and the final score on Kaggle is 0.73313.
# Code Structure
* [`mylib/`](mylib/):
    * [`densenet.py`](mylib/densenet.py): 3D *DenseNet* models
    * [`RocAuc.py`](mylib/RocAuc.py): Roc-Auc evaluation.
* [`main.py`](main.py): Compile model, train and predict.
* [`test.py`](test.py): Get "Submission.csv" file, corresponding to my best score in Kaggle.
# Other files
* [`dataset/`](dataset/):
    * [`train_val/`](dataset/train_val/): Training dataset.
    * [`test/`](dataset/test/): Testing dataset.
    * [`train_val.scv`](dataset/train_val.scv): Labals of training dataset.

# Requirements
* Python 3 (Anaconda 3 specifically)
* TensorFlow==1.15.0
* Keras==2.2.0
