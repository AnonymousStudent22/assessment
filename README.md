# assessment
**Tasks**

The task in this repository is to buid two models that wil be trained on the image data and learn to classify it. One model will perform binary classification to detect whether a tumour is present in the brain scan images and the chosen model is logistic regression. The other model is a KNN model designed to perform multiclass classification.

**Role of each file and file organisation**

Each model has its own Jupyter Notebook file. The binary classification model is in the file named logistic_regression.ipynb and the multiclass classification model is saved in multiclass_classfication.ipynb.]

The directory called dataset contains:

- the file sample_;labels_0_1.csv (image file names with binary labels)
- the sample_labels_updated (image file names with multiclass labels)
- the subdirectory called sample_images, with all the image files.

The directory called test contaiins:

- the file labels_0_1.csv (image file names with binary labels)
- the file label.csv (image file names with multiclass labels)
- the subdirectory called image, which contains all the test image files

**How to run the code:**

In the Jupyter Notebook file, click on Cell/Run All to run through the whole process of reading in the data, preprocessing it, defining the model, training and testing it. Otherwise, select each code cell individually and click on the “Play” button to run each one in the order of top to bottom.

**The required libraries are:**

 - os
- skimage
- io (from skimage)
- imread (from skimage)
- imshow (from skimage)
- matplotlib.pyplot
- pandas
- numpy
- import train_test_split (sklearn.model_selection)
- shuffle (sklearn.utils)
- classification_report,accuracy_score (from sklearn.metrics)
- natsort
- confusion_matrix (from sklearn.metrics)
- fconfusion_matrix, and ConfusionMatrixDisplay (from sklearn.metrics)
