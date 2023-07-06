# Intro-to-GAN
Generative Adversarial Networks
Generative Adversarial Networks, are a type of computer program that can create new images or data. They consist of two main parts: a Generator and a Discriminator.

The Generator's job is to create new images or data that look real. It starts by making random images or data, and then it gets feedback from the Discriminator. The Discriminator's job is to decide whether an image or data is real or fake. It looks at both real examples from a training set and the images or data created by the Generator. Based on this, it tries to guess whether each image or data is real or fake.

The Generator and Discriminator are trained together, but they have opposite goals. The Generator wants to create images or data that the Discriminator will think are real, while the Discriminator wants to correctly identify which images or data are real and which are fake.

During training, the Generator keeps improving its ability to create realistic images or data. It tries to fool the Discriminator by making its creations look as real as possible. The Discriminator, on the other hand, keeps getting better at distinguishing between real and fake examples.

As training progresses, the Generator becomes so good at creating realistic images or data that the Discriminator can no longer tell the difference between real and fake. This means that the Generator has successfully learned to generate high-quality images or data that are similar to the ones it was trained on.
