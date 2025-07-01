# This project builds a Convolutional Neural Network (CNN) using Keras to classify handwritten digits from the MNIST dataset.

#  Dataset
60,000 training images,10,000 testing images,Each image: 28x28 grayscale digit (0-9)

# Preprocessing
Reshaped data to (28, 28, 1) for CNN input.
Normalized pixel values: scaled to [0, 1] range.
One-hot encoded labels: converted labels to categorical format (10 classes).

# Possible Improvements
Add Dropout layers to prevent overfitting,Increase epochs for finer convergence,Use data augmentation (e.g., rotations, shifts).
