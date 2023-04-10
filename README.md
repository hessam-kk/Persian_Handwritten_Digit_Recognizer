# Persian_Handwritten_Digit_Recognizer
Persian Handwritten Digits Recognizer Using 
* Python3
* Neural Networks 
* Tensorflow / Keras
* Cv2
* Numpy


## Preprocessing
- Displaying the raw samples
- Normalizing the pixel values
- Applying thresholding to simplify the data
- Performing erosion and dilation to clean up broken or disconnected pixels
- Optionally applying morphological closing (can potentially reduce accuracy)


## First Model
Consists of three layers: two dense layers with ReLU activation functions and one dense layer with softmax activation function.

Best accuracy: loss: 0.0695 - accuracy: 0.9792 (with closing)


## Second Model
Consist of four layers: three dense layers with ReLU activation functions and one dense layer with softmax activation function.

Best accuracy: loss: 0.0652 - accuracy: 0.9847 (with closing)


## Third Model
Consist of three layers: two dense layers with ReLU activation functions and one dense layer with softmax activation function.
Best accuracy: loss: 0.0541 - accuracy: 0.9880 (without closing)

