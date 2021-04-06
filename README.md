# Keras-implementation-of-Dense-and-DC-NSGAN-WGAN-WGAN-GP-etc.-for-generating-Mnist-Digits
Contains simple GAN models.

For NS-GAN,WGAN,WGAN-GP the initial approach was to make a custom training loop and do the training.However, after training more than 100 models,I realized that this method
is very prone to logical errors. Because of this reason, I wrote object oriented code and soon realized that this method is no more prone to logical errors and can be directly embedded for making more complicated models.Both code are uploaded here.
