# Bird_Species_Classification_CNN
This repository contains the creation of a CNN based model to classify 25 Indian species of birds.
This project was carried out as part of the Digital Image Processing course.

The dataset has 22.6k images of 25 different bird species in India. The dataset is available in Kaggle.
This dataset was first analysed and image enhancement and restoration is performed.
Later data augmentation was performed to introduce variety in the dataset. As part of data augmentation
images were rotated and flipped both horizontally and vertically.

Then a CNN classification model was developed.
Key parameters of the model:
1) Optimizer: Adam
2) Loss: Sparse Categorical Cross Entropy
3) Metrics: Accuracy

The model was trained for 20 epochs with Nvidia Tesla P100 GPU which is available in Kaggle.
The .h5 model can be downloaded from my Kaggle account.
