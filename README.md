# NAIVE-BEES_A-COMPUTER-VISION-MODEL
Deep learning with bee images.

This is a part of DataCamp's structured projects and it's in 3 parts. 

The first part of the project focuses on image loading in python, working with the Pillow (PIL) library and some pre-processing steps necessary to perform deep learning. My main motivation for undertaking this project was to learn how to work with images in python. It was very interesting to perform basic operations such as cropping, resizing, rotating and coverting images to different color modes. I also used kernel density plots to visualize the color composition of images. Increasing image contrast using np.maximum() function was one of the neatest trick I learnt in this part of the project.

The second part of the project was aimed at training a computer vision model that can be used to identify honey bees and bumble bees in images. Some of the pre-processing steps included using the histogram of oriented gradients (HOG) descriptor to identify an object's shape in the greyscale version of an image, combining the features obtained from the HOG function with the features obtained by flattening the matrix of the color version of the image. Afterwards, the feature matrix was scaled and PCA was applied to reduce the number of features. Finally, a support vector classifier (SVC) model was fitted using a linear kernel to the train set and we obtained an accuracy of 68% on our predictions. We also plotted the receiver operating characteristic (ROC) curve and obtained a 0.74 area under the curve (AUC).

While the second part of the project focused on building a traditional ML classifier, the third part of the project aimed to build a simple deep learning model to the the same job of classifying honey bees and bumble bees. A Sequential model type of the Convolutional Neural Network is used here. Although the model did not outperform the previous SVC model that was built in part 2 in terms of accuracy,, it was great to learn the architecture and workings of a deep learning model.

Have fun reading!
