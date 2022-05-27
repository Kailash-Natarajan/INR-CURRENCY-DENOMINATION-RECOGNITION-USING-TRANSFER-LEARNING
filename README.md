# INR-CURRENCY-DENOMINATION-RECOGNITION-USING-TRANSFER-LEARNING
INR Denomination Recognition is an image classification project.

* In this project, Indian Rupees Notes are classified according to their currency value, using deep learning techniques. 
* This project leverages the power of transfer learning. The pretrained base model used is EfficientNetB0. 
* This project is a demonstration of image classification and transfer learning (feature extraction and fine tuning) using Tensorflow Keras 
* Performs significantly better than CNN models build and trained from scratch
* The dataset used for this project is sourced from https://www.kaggle.com/code/kerneler/starter-indian-currency-note-images-f2ab9d26-d/data
* Dataset contains roughly 450 training images for each class, namely, Rs 10, Rs 20, Rs 50, Rs 100, Rs 200, Rs 500, Rs 2000 and Background. The background class signifies there is no Indian Rupees Currency Note in the provided image. There are also roughly 45 images per class for validation set. There are 91 imaages for the purpose of testing
