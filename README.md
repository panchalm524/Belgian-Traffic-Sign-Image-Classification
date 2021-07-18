# Belgian-Traffic-Sign-Image-Classification
The dataset is a collection of 62 different types of traffic signs used on Belgian roads in 62 sub folders in training and test folders. The images are in .ppm format and are read from the subfolders and converted into numpy arrays. Images are labelled as the subfolder names. Feature extraction was needed as they had different sizes. So, images were rescaled to 28x28 and then converted to grayscale. An ANN was built using tensorflow after flattening the input image. Then a fully connected layer of logits was constructed. The model gave the accuracy of 61% which call for further improving the model by adding hidden layers in ANN or using CNN.

Dataset link: http://btsd.ethz.ch/shareddata/
Open the pic.png in the repository to see where to download the data from.
