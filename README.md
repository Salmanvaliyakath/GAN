# GAN

GANs can create images that look like photographs of human faces, even though the faces don’t belong to any real person.

We know how to generate new photo-realistic images with a Variational AutoEncoder. VAEs typically produce blurry and non-photorealistic faces. This is a motivation to built Generative Adversarial Networks (GANs).


### A GAN has three primary components: a generator model for generating new data, a discriminator model for classifying whether generated data are real faces, or fake, and the adversarial network that pits them against each other.

The generative part is responsible for taking N-dimensional uniform random variables (noise) as input and generating fake faces. The generator captures the probability P(X), where X is the input.

The discriminative part is a simple classifier that evaluates and distinguished the generated faces from true image. The discriminator captures the conditional probability P(Y|X), where X is the input and Y is the label.


![image](https://user-images.githubusercontent.com/49808077/211279515-295826d9-e5d9-430a-85da-ce996cb7c4e3.png)

