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
