# Image Retrieval System using Deep Learning Models- Research project
#### Computer Vision

- Developed an image retrieval system that identifies and retrieves images based on a query image, utilizing Convolutional Neural Networks (CNN) with regularization, and transfer learning. 
- The system was trained on the Google Landmark Dataset v2 Mini. 
- The highest accuracy (88.68%) was achieved using the ResNet50 architecture in combination with K-Nearest Neighbors (KNN) for classification.
- 
##### Dataset Used:
#####   a. Training- Google Landmarks v2 Mini (Downsampled to 50 classes)
#####   b. Evaluation- Revisited Oxford and Paris Dataset


### Files added in folder:

WITH_CNN.ipynb
Link:
This notebook contains the preprocessing steps performed on the Google dataset, including data analysis such as visualizing data distribution, downsampling, and image resizing. Additionally, it implements a custom CNN architecture applied to the downsampled dataset, both with and without regularization.

transfer_learning.ipynb
Link:
This notebook demonstrates the application of transfer learning using standard architectures on the dataset. The architectures used include VGG-16, VGG-19, ResNet50, and DenseNet.

baseline_model_evaluation.ipynb
Link:
This notebook presents the evaluation of the trained models on the Revisited Oxford and Paris Dataset.

##### Model Performance Visualization:
<img width="302" alt="Screenshot 2022-07-27 at 11 09 36 AM" src="https://user-images.githubusercontent.com/73076997/181169698-40aac7f6-1bb1-46eb-9e91-80aa571c7d08.png">

Research Paper Link- https://drive.google.com/file/d/15i7yasSbQWF_opF0E8U2aUinzkqzEmy2/view?usp=sharing
