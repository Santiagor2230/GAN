# GAN
Implementation of Regular GAN

# Requirement:

Tensorflow

numpy

matplotlib

# Description:
The GAN architecture most notabily called Generative Adversarial Network is a unique generative model that is broken into two parts the discriminator and the generator. The generator is trying to prove that its generating real data while the discriminator is trying to judge wheter data is real or created by the generator. This constant battle between the discriminator and the generator allows the model to be competitive in who can be better at doing their task, at the end of the training the discriminator should be able to easily detect fake and real data while the generator should be able to create close to perfect real data that it decieves the discriminator.

# Architecture
GAN

# Dataset:
MNIST Dataset

# Generator Results:

## Real MNIST Data:
![mnist](https://github.com/Santiagor2230/GAN/assets/52907423/e7430edb-af2d-498d-88fb-5aa0167be458)

## Generator Data:

As we train the architecture we can see how the generator is slowly trying to predict the real MNIST dataset:

### Training 0:
![start](https://github.com/Santiagor2230/GAN/assets/52907423/6944165f-142a-415c-83bc-5121e8a2a37e)

### Training 1000:
![part2](https://github.com/Santiagor2230/GAN/assets/52907423/ca679f77-d1fe-4ad6-84d4-0f4e2c259dad)

### Training 10000:
![part3](https://github.com/Santiagor2230/GAN/assets/52907423/9b7c299b-079a-4b67-b866-f75947a7a32d)

### Training 20000:
![part4](https://github.com/Santiagor2230/GAN/assets/52907423/e30f063b-8191-4962-bbe0-5ee32f759ee4)

### Training 29000:
![part5](https://github.com/Santiagor2230/GAN/assets/52907423/8c481ea4-3199-4c4c-ac72-795cc179ba7b)


