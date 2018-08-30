TODO:
- Infogan notebook does not train
- Clean up acgan
- acgan and infogan code borrows heavily from [keras-gan](https://github.com/eriklindernoren/Keras-GAN) so be careful


Course Plan:

Intro

- 00 **Deep Learning Review** with focus on convolutional layers, transfer learning, and practical training techniques (batch norm, dropout, etc.)
- 01 **Weight visualization** Idea here is to introduce the first "generative" tool for a network. Here, it's just a forward convnet and we're visualizing the inputs that maximize activation of different parts of the network. 
- 02 **Autoencoders** Visualization is a generative tool, but how can we teach a network to generate something? Autoencoders are the original generative networks, great for summarizing training data onto a latent space.
- 03 **Variational Autoencoders** VAEs allow us to sample from the learned latent space (AEs generate deterministically)

GAN

- 03 **GAN p 1** First experience with GANS. Build a shallow Generator-Discriminator netowrk.
- 04 **GAN p 2** Deep Convolutional GANS.
- 05 **Super Resolution GANS** introduction to super-resolution task.

Semi-Supervised GAN

- 06 ** Auxillary Classifier GAN**
- 07 ** Info GAN**

Links:
- [Keras-GAN](https://github.com/eriklindernoren/Keras-GAN) tons of helpful code for a bunch of different GANS
- Tips for training GANS
  - [ganhacks repo](https://github.com/soumith/ganhacks) (old)
  - [toward data science](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf)
- Theory
  - [Goodfellow GAN tutorial](https://arxiv.org/abs/1701.00160)
  - [Chollet book and notebooks](https://github.com/fchollet/deep-learning-with-python-notebooks) the last chapter intros GANs
  - [Deep Learning Book](http://www.deeplearningbook.org/contents/generative_models.html) at the very very end is a bit on GANS
