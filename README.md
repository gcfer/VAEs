# Variational Autoencoders

Notebook experiments with variational autoencoders using TensorFlow/Keras.

## Notebook

| File | Description |
| --- | --- |
| `vae_mnist_custom_layer.ipynb` | A VAE for MNIST digits using a custom Keras layer for the custom loss. |

The notebook focuses on estimating the distribution of MNIST digits, starting
with the digit `0`, and walks through the VAE model construction and training
workflow.

## How to run

Open `vae_mnist_custom_layer.ipynb` in Google Colab and run the cells from top
to bottom. The notebook uses TensorFlow 2.x and loads MNIST from
`tf.keras.datasets`.
