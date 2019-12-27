# -Medical 3D Voxel Classification-
This is the course assignment of EE369 machine learning 2019 autumn course of Shanghai Jiaotong University, Medical 3D Voxel Classification(M3DV) Kaggle inclass competition.  
This is a classification project of pulmonary nodules. We use a deep learning system to complete this project, and the final score on Kaggle is 0.73313.
# Code Structure
* [`main.py`](main.py): Compile model, train and predict. Output the predict results to "Submission.csv".
* [`test.py`](test.py): Load weights and output predict results, corresponding to my best score in Kaggle, to "Submission.csv".
* [`mylib/`](mylib/):
    * [`densenet.py`](mylib/densenet.py): 3D *DenseNet* models. Reference from:https://github.com/duducheng/DenseSharp
    * [`RocAuc.py`](mylib/RocAuc.py): Roc-Auc evaluation. Reference form: https://blog.csdn.net/qq_16234613/article/details/79437952
# Other Files
* [`dataset/`](dataset/):
    * [`train_val/`](dataset/train_val/): Training dataset.
    * [`test/`](dataset/test/): Testing dataset.
    * [`train_val.csv`](dataset/train_val.csv): Labals of training dataset.
    * ***Note**: The dataset is not available publicly, so only a demo of training dataset and testing dataset, as well as the label of training dataset demo are provided here.*
* [`weights`](weights/): Saved model weights.
* [`sampleSubmission.csv`](sampleSubmission.csv): A sample submission file.
# Requirements
* Python 3 (Anaconda 3 specifically)
* TensorFlow==1.15.0
* Keras==2.2.0
