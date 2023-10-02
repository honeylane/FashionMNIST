# FashionMNIST
Fashion MNIST CNNs

1. Simple:
2 Conv Layer
2 Max Pooling Layer
Optimizer = Adam
Loss = Sparse Categorical Entropy
Epoch = 10

2. With Augmentation
data_augmentation = tf.keras.Sequential([
layers.RandomFlip("horizontal")
])

3. Hyperparameter searching with Keras Tuner

4. Transfer learning with Resnet101

5. Hyperparamenter tuning on Resnet101 model
