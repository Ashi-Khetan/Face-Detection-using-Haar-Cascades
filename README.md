# Face-Detection-using-Haar-Cascades
Haar feature-based cascade classifiers is an effective object detection method and was proposed by Paul Viola and Michael Jones. This method is used for face detection and not face recognition.
Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. The main types of feature used here are : Edge features, Line features, and Four-rectangle features. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under white rectangle from sum of pixels under black rectangle.
OpenCV comes with pre-trained XML files of various Haar Cascades classifiers.
