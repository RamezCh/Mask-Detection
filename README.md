# Mask Detection
Over the course of one week, I was given a dataset containing images of people with and without face masks. My goal was to build a model that could accurately classify whether an individual in an image was wearing a mask or not.

I started by organizing the dataset into three parts: training, validation, and testing. The data was randomly divided to ensure balanced representation of both classes during model training and evaluation.

I then developed a custom convolutional neural network (CNN) tailored for this classification task. The model used multiple layers to extract important visual features from the images, including convolutional layers, pooling layers, and fully connected dense layers. To reduce overfitting and improve generalization, I included dropout regularization.

Before feeding the images into the model, I applied preprocessing steps using Keras' ImageDataGenerator. This helped scale pixel values to a standard range and loaded the data efficiently in batches during training.

The model was trained using the binary cross-entropy loss function and the Adam optimizer. I monitored performance using accuracy, precision, and recall as key metrics throughout training. After initial training, I evaluated the model on the validation set and made adjustments to improve its performance.

This project gave me valuable experience in designing and tuning deep learning models for real-world computer vision tasks under time constraints.
