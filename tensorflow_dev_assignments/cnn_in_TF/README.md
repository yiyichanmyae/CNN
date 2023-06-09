# Convolutional Neural Network in TensorFlow

## Week 1 : Image Classification
[cats_v_dogs_classification](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W1_Assignment_cats_v_dogs_classification.ipynb)
- Image Binary Classification with Simple CNN
- Used `ImageDataGenerator`
- total cat images : 15000
- total dog images : 15000

## Week 2 : Data Augmentation
[cats_v_dogs_augmentation.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W2_Lab1_cats_v_dogs_augmentation.ipynb)
- Image Binary Classification
- applying `Data Augmentation` by using `ImageDataGenerator`
- it shows Data Augmentation can help to avoid `Overfitting`.
- training images : 2000
- validation images : 1000

[horses_v_humans_augmentation.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments%20/cnn_in_TF/C2W2_Lab2_horses_v_humans_augmentation.ipynb)
- Image Binary Classification
- applying `Data Augmentation` by using `Image Data Generator`
- it shows Data Augmentation does not guarantee to solve `Overfitting`.

[cats_v_dogs_classification_augmentation.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W2_Assignment_cats_v_dogs_classification_augmentation.ipynb)
- Image Binary Classification
- applying `Data Augmentation` by using `ImageDataGenerator`
- total cat images : 15000
- total dog images : 15000

## Week 3 : Transfer Learning
[transfer_learning_cats_v_dogs.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W3_Lab1_transfer_learning.ipynb)
- Problem : Binary Classification
- use the pretrained [InceptionV3](https://storage.googleapis.com/mledu-datasets/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5) model as the based model
- freeze the layers not to get retrained
- chose a layer as the last layer to use as the base model
- create a DNN including Dropout Layers
- preprocess the customized data to be trained ( e.g., the cat vs dog data )
- train the model and evaluate it

[transfer_learning_horses_v_humans.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W3_Assignment_horses_v_humans.ipynb)
- Problem : Binary Classification
- use the pretrained [InceptionV3](https://storage.googleapis.com/mledu-datasets/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5) model as the based model
- `Transfer Learning`, `Data Augmentation`
- this is the solution of the [assignment3](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W3_Assignment.ipynb)

## Week 4 : Multiclass Classification
[multiclass_classifier.ipynb](https://github.com/yiyichanmyae/CNN/blob/main/tensorflow_dev_assignments/cnn_in_TF/C2W4_Lab1_multi_class_classifier.ipynb)
- Problem : Multiclass Classification
- Dataset : Rock Paper Scissors dataset


# Datasets

### Rock Paper Scissors
Rock-Paper-Scissors is a dataset containing 2,892 images of diverse hands in Rock/Paper/Scissors poses. It is licensed 
CC By 2.0 and available for all purposes, but its intent is primarily for learning and research.

Rock Paper Scissors contains images from a variety of different hands,  from different races, ages, and genders, posed into Rock / Paper or Scissors and labeled as such. You can download the [training set](https://storage.googleapis.com/tensorflow-1-public/course2/week4/rps.zip) here, and the [test set](https://storage.googleapis.com/tensorflow-1-public/course2/week4/rps-test-set.zip) here. These images have all been generated using CGI techniques as an experiment in determining if a CGI-based dataset can be used for classification against real images. I also generated a few images that you can use for predictions. You can find them 
here.
Note that all of this data is posed against a white background.
Each image is 300×300 pixels in 24-bit color
