# MINST-GANs

In this project we created a GAN that can generate images based on the Minst data set.


For this purpose we created 2 simple neural networks, a discriminator and a generator the first one generates images from noise and the second one classifies the given images into real and fake images and gives feedback to the generator model.

**Results**:
The final loss in the generator was 2.3 and in the discriminator 0.3.

Here you can see some example of the generated images:

![image](https://user-images.githubusercontent.com/47577344/103835664-e2f34200-5054-11eb-9b7a-326564be2421.png)

What i´ve learned:
- It is important to balance the loss of the generator and the discriminator in order to be close between them.
- some of the GANs power resides on his forward execution time, which if we compare with other generative techniques as neural style transfer which is on average 15 minutes per image. 


