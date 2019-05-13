# VAE

Full name for VAE is Variational Auto-Encoder. It is a special case of AEVB(Auto-Encoding VB) algorithm when the recognition model. There will also be a short introduction for this in the jupyter notebook. For more details please read the original paper [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)

In the jupyter notebook, I use pytorch to implement this encoder and trained it separately on MNIST and some images collected from Pong game to see the effect. Some illustrations were done there. The next step will be training some RL agent in the encoded space and compare the result which is obtained by training in the original space.
