# Build-AI-Model
Built a Model with Google AutoML Vision
Optimized Google AutoML, an automated machine learning tool - to build a classification model to classify data for medical image use case. Model is built with four (4) variants of dataset, to appreciate how training data impact models. Open source data from Kaggle chest x-ray dataset was used. Model was evaluated based on confusion matrix, precision & recall, and other variable data factors.

Four (4) variants of dataset include;
1. binary classifier to detect pneumonia using chest x-rays: Model trained on balanced data using 100 images from the “normal” class and 100 images from the “pneumonia”. Model was evaluated based on train/test split for data used; confusion matrix, precision & recall.
2. Unbalanced binary classifier: Model trained on unbalanced data using 100 images from the “normal” class and 200 "pneumonia" class images for a total of 300 images in the “pneumonia” class. Model was evaluated based on confusion matrix, precision & recall, and unbalanced classes.
3. Binary classifier with dirty data: Model trained on dataset of 100 "normal" and 100 "pneumonia" images; then switched the labels of 30 images in each class in which 30% of the data are mislabeled. Model was evaluated based on confusion matrix, precision & recall, and dirty 
data.
4. Three-class model: Model trained on total of 3 classes - 100 "normal" images, 100 "bacterial pneumonia" images, and 100 "viral pneumonia" images. Model was evaluated based on confusion matrix, precision & recall, and additional data used.
