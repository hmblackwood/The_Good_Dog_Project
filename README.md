# 🐶 The Good Dog Project 🐶
### Please visit the project file to learn more. https://github.com/hmblackwood/The_Good_Dog_Project/blob/main/The_Good_Dog_Project.ipynb


Summary:
Using transfer learning, I created a convolutional neural network (CNN) deep learning, multi-class image classifier model with MobileNet V2 to identify the breed of dog based on an image.

Libraries Used: Tensorflow, Keras, NumPy, Matplotlib, Seaborn, Pandas, and Scikit-Learn

1. Problem:
Identify the breed of a dog based on an image.

2. Data:
The data is from the Stanford Dogs Dataset from the Dog Breed Indentification Completition on Kaggle. https://www.kaggle.com/c/dog-breed-identification/data Citation: @misc{dog-breed-identification, author = {Will Cukierski}, title = {Dog Breed Identification}, year = {2017}, howpublished = {\url{https://kaggle.com/competitions/dog-breed-identification}}, note = {Kaggle} }

3. Machine Learning model:
SSD-based ("Single Shot Detector") object detection model trained on Open Images V4 with ImageNet pre-trained MobileNet V2 as image feature extractor. https://www.kaggle.com/models/google/mobilenet-v2/tensorFlow2/130-224-classification/1?tfhub-redirect=true

4. Evaluation:
Model is evaluated on Multi Class Log Loss between the predicted probability and the obeserved target. www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

5. Features:
Information about the data:

Unstructured data (images).
120 different classes, one for each breed of dog, into which images will be sorted.
10,000+ images of dogs in the training set, all of them labeled.
10,000+ images of dogs in the test set, all unlabeled. The model will be making predictions based on these.
