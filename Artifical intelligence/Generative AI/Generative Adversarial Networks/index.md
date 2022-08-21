# Generative Adversarial Networks (GANs)

Generative Adversarial Networks are a type of machine learning network in which two neural networks compete. One network is tasked with generating realistic-seeming content (unsupervised learning), which the other network is tasked with distinguishing the generated content against real data (Supervised learning). The two networks are pitted against each other, and the generated content is improved over time.

Input -> Generator -> Output -> Discriminator -> True / False
Training dataset injected within the output -> Discriminator flow
Loss function flows back to the Generator

Generator - Unsupervised Learning
The generator within a GAN is a machine learning model that's trained to produce realistic-seeming output.

Discriminator - Supervised Learning
The discriminator is another machine learning model which is trained to take an input and classify whether or not the input is real or generated.

The discriminator looks for features from the dataset it was trained on in the content samples the generator created. It decides whether the content is real or fake. The generator is then trained to create content that is more realistic and less easily detected by the discriminator.

The results of the discriminator's judgements are used to train both models. The generator is trained to optimize for producing realistic content that the discriminator cannot distinguish from the real samples. Meanwhile, the discriminator is trained to increase its ability to detect generated content.

This back-and-forth behavior, where the two models are directly competing against each other, is the adversarial part of GANs.
