# Image-Captioning-using-CNN-LSTM
The Convolution Neural Network (CNN) (Densenet201 Architecture)  is implemented for detecting features from the printed image and its associated caption. The Long Short-Term Memory (LSTM) network is used as a captioning tool to describe the detected text from images .

<h3>About the dataset</h3>
A new benchmark collection for sentence-based image description and search, consisting of 8,000 images paired with five different captions that provide clear descriptions of the salient entities and events. The images were chosen from six different Flickr groups, and tend not to contain any well-known people or locations, but were manually selected to depict various scenes and situations.

<h3>Environment</h3> 
The model is trained on Kaggle using GPU T4 x2 accelerator to speed up the training process.

<h3>Compilation</h3>
The model is compiled using Adam optimizer and binarycategorical_crossentropy loss.

<h3>Results</h3>
On the test data, the model produced a BLEU score of 0.5634. 
