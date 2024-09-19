# CNN-Model-on-CIFAR-10-data
Image Classification

Problem : Creating a CNN model usig CIFAR-10 dataset

Data: The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Solution: The model uses a sequential architecture with convolutional, pooling, and fully connected layers to classify images from the provided dataset. It leverages data preprocessing techniques such as resizing, normalization, and augmentation to enhance model performance. The model is trained using the Adam optimizer, achieving high accuracy on both training and validation sets. The Jupyter notebook includes steps for building, training, and evaluating the model, with provisions for further customization, such as fine-tuning or transfer learning.
