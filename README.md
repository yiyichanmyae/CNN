# CNN
Notebooks for CNN theories in different implementing ways/ classification problems
____________________________________________________________
# Directories

## [tensorflow_dev_assignments](https://github.com/yiyichanmyae/CNN/tree/main/tensorflow_dev_assignments)
- Directory which includes the notebooks from `TensorFlow Developer Certificate Specialization`

### [cnn_in_TF](https://github.com/yiyichanmyae/CNN/tree/main/tensorflow_dev_assignments/cnn_in_TF)
- Notebooks from `CNN in TensorFlow`

______________________________________________________________
# Classification Projects

## Image Classification
[cats_v_dogs_classification](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W1_Assignment_cats_v_dogs_classification.ipynb)
- Image Binary Classification with Simple CNN
- Used `ImageDataGenerator`

## Data Augmentation
[cats_v_dogs_augmentation.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W2_Lab1_cats_v_dogs_augmentation.ipynb)
- applying `Data Augmentation` by using `ImageDataGenerator`
- it shows Data Augmentation can help to avoid `Overfitting`.

[horses_v_humans_augmentation.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments%20/cnn_in_TF/C2W2_Lab2_horses_v_humans_augmentation.ipynb)
- applying `Data Augmentation` by using `Image Data Generator`
- it shows Data Augmentation does not guarantee to solve `Overfitting`.

## Transfer Learning
[transfer_learning.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W3_Lab1_transfer_learning.ipynb)
- use the pretrained [InceptionV3](https://storage.googleapis.com/mledu-datasets/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5) model as the based model
- freeze the layers not to get retrained
- chose a layer as the last layer to use as the base model
- create a DNN including Dropout Layers
- preprocess the customized data to be trained ( e.g., the cat vs dog data )
- train the model and evaluate it

## Multiclass Classification
[multiclass_classifier.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W4_Lab1_multi_class_classifier.ipynb)
Problem : Multiclass Classification
Dataset : Rock Paper Scissors dataset

[multiclass_signlanguage.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W4_Assignment_SignLanguage.ipynb)
- Problem : Multiclass Classification
- Dataset : [Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
- Different data input with [multiclass_classifier.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W4_Lab1_multi_class_classifier.ipynb)

# Datasets

### Rock Paper Scissors
Rock-Paper-Scissors is a dataset containing 2,892 images of diverse hands in Rock/Paper/Scissors poses. It is licensed 
CC By 2.0 and available for all purposes, but its intent is primarily for learning and research.

Rock Paper Scissors contains images from a variety of different hands,  from different races, ages, and genders, posed into Rock / Paper or Scissors and labeled as such. You can download the [training set](https://storage.googleapis.com/tensorflow-1-public/course2/week4/rps.zip) here, and the [test set](https://storage.googleapis.com/tensorflow-1-public/course2/week4/rps-test-set.zip) here. These images have all been generated using CGI techniques as an experiment in determining if a CGI-based dataset can be used for classification against real images. I also generated a few images that you can use for predictions. You can find them 
here.
Note that all of this data is posed against a white background.
Each image is 300×300 pixels in 24-bit color

### Sign Language MNIST
[Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist) 
The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. 
