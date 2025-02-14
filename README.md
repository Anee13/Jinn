# Emotion_Detection_CNN

Facial emotion detection is a task in computer vision that involves identifying the emotions expressed by a person's face in an image or video. Deep learning models, particularly convolutional neural networks (CNNs), have shown great promise in this task.

#Step 1- Data preprocessing: The first step is to preprocess the input data. This includes cropping the face region, normalizing the pixel values, and resizing the images to a fixed size.

#Step 2- Feature extraction: The next step is to extract features from the preprocessed images. This can be done using a combination of CNN and LBP algorithms.
    CNN: The CNN component can be used to learn high-level features from the images. A typical CNN architecture for facial emotion detection includes multiple convolutional layers followed by max pooling and fully connected layers. The output of the last fully connected layer can be used as a feature representation of the input image.
    LBP: The LBP component can be used to capture texture information of the face. LBP works by comparing the pixel values of a center pixel with its neighboring pixels and encoding the result as a binary number. The LBP features can be concatenated with the CNN features to form a joint feature representation.

#Step 3- Training: The joint feature representation is fed into a classifier, which is trained on a labeled dataset of facial emotion images. The classifier can be a simple linear model or a more complex model such as a support vector machine (SVM) or a neural network.

#Step 4- Evaluation: The trained model can be evaluated on a separate test set to measure its performance in recognizing emotions. Common evaluation metrics include accuracy, precision, recall, and F1 score.

Data Set Link - https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset
