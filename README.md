# Style-Transfer-Algorithm
# Overview
This repository contains the implementation of the style transfer algorithm, which allows users to apply a particular artistic style to images. The algorithm is based on a convolutional neural network autoencoder model which was trained on particular content dataset inorder to transform it into artistic styles of a particular artist.
# Results
![image](https://github.com/bhriya/Style-Transfer/assets/84380595/c468010a-a81b-42a7-b2ae-f64babde1e01)

# Limitations and possible improvements
This particular model is limited with respect to the amount of training data used for training the model, thus increasing the amount and diversity of training data can further improve the results in terms of the content preservation while simultaneously copying the style of the artist. Another improvement can be using different artistic styles from different artists and creating a classification model based on different style features and thus adding another multi-output classification loss which would result in better style transformation methodology based on a particular style. Another possible improvement involves detecting the edges of the content images using canny edge detection algorithm and then preserving the edges by weighting the edges preservation. 

# Dataset for style and content images can be accessed through the following links
Artworks Dataset- https://www.kaggle.com/datasets/huynguyenphamnhat/artworks-dataset/
Content Dataset- https://www.kaggle.com/datasets/duttadebadri/image-classification/

# Setup to run
The notebook will work directly in kaggle by uploading the above dataset and downloading the weights provided in the repo in .h5 format.
