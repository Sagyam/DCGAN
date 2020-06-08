# Deep Convolutional Generative Adversarial Networks (DCGANS)
This Network generate images of clothing item using a Deep Convolutional Generative Adversarial Network (DCGAN). The code is written using the Keras Sequential API 

This project is based on a guided project offered on [Coursera](https://www.coursera.org/learn/generative-adversarial-networks-keras/).

[Click here](https://colab.research.google.com/drive/1wp5wRPvaQhJbtqm7Pvy5NCWB5yckdG2y?usp=sharing) to view the interactive notebook.  

# What are GANs?
Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.

![](https://www.tensorflow.org/tutorials/generative/images/gan1.png)

During training, the generator progressively becomes better at creating images that look real, while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can no longer distinguish real images from fakes.

![](https://www.tensorflow.org/tutorials/generative/images/gan2.png)

Architecture of DCGAN

![](https://camo.githubusercontent.com/751861840717de70c2f18a0c94061b4c23e66114/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313030302f312a723841497a557042634e7a70692d4a4e33674c5774672e706e67)

Some generated images after traning for 5 epochs

![](https://user-images.githubusercontent.com/45777019/84037270-0f12eb80-a9be-11ea-8e83-1edb51b27061.png)

