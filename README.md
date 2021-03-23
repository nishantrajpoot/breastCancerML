# breastCancerML
ML Project on detection of Breast Cancer using three algorithms (Random forest/SVM/SGD).

The aim of the project is to do a Binary classification of breast cancer dataset using the Machine language algorithm.

The whole project was divided into two subtasks:
1. How well can the model classify individual micros assuming all micros per subject have the same label?
2. How well can the model classify whether a subject has cancer-based on your classification of the multiple micros per subject?

For detecting breast cancer, the state-of-the-art technique mammography is used. Mammography generates the X-ray images of the breast. Tiny white calcium deposits in the breast which are very difficult to detect in normal X-ray due to the anatomy of its structure. The presence of a certain group of micros is indicative of breast cancer. So, there can a tumor without micros and no tumor with micros. With the help of mammography, the microcalcification that is present in the neighborhood of tumors can be classified as malignant micro and the microcalcification that are not in the neighborhood of tumor as benign micro.
To do the following experiment, the tabular dataset from images was given and not the images themselves. The data consist of 96 distinct patients with a total of 3652 micros, which means each patient has multiple micros. Also, the dataset has 154 features.
The challenge was to make a Machine learning model that would classify the data with good accuracy and find whether a given patient is Malignant or Benign, given that its real label is already known.
The code for the project was written in Python 3.7.5 language and the environment used was “jupyter notebook” by Anaconda Navigator on Windows 10 machine. The famous machine learning library “scikit-learn” was used to import the following functions: “test_train_split”, “GridsearchCV”, SGDClassifier, SVC, RandomForestclassifier, normalize and ExtraTreesClassifier.


***NOTE***
Data is confidential therefore not provided with this repository.
