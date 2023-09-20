# Notebooks!

Colab runtimes - Single GPUs, TPUs, CPUs
Kaggle Runtimes - Single GPUs, Dual GPUs, TPUs, CPUs

Highly recommended to do the following with the multi device code:

Change the batch size with various accelerators. Get a feel of parallel training!

## Links

[Getting Started - Colab](https://colab.research.google.com/github/SuperSecureHuman/keras-day/blob/main/Notebooks/Getting%20Started.ipynb)

[Getting Started - Kaggle](https://www.kaggle.com/code/supersecurehuman/basic-modelling-with-keras-core-jax/notebook)

[JAX Loop and Multi Device - Colab](https://colab.research.google.com/github/SuperSecureHuman/keras-day/blob/main/Notebooks/JAX%20Loop%20and%20MultiDevice.ipynb)

[JAX Loop and Multi Device - Kaggle](https://www.kaggle.com/code/supersecurehuman/multi-device-jax-keras/notebook)

## Note

You have to use the distributed way of running whenever using TPUs. Running the simple code on TPUs will not work (will throw shardding error)
