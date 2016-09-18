# Deep-Learning-Papers
A list of deep learning papers, videos, reddit pages, stack overflow questions  and tutorials that I have found helpful in my studies. This list will mostly contain fairly new (as of me seeing it) stuff.

# Variational Autoencoders
Variational Autoencoders

## [TJ Torres: Deep Style](https://www.youtube.com/watch?v=-_4YbiJKmV8) (Dec 4, 2015)

This was the first video I saw on variational autoencoders. I found his explinations extremely intuative and would recogment to anyone who just wants to get some nets trainin.

## [Tutorial on Variational Autoencoders](https://arxiv.org/pdf/1606.05908v2.pdf) (August 16, 2016, gets updated a lot though)

Gives very intuative explination of variational autoencoders. I particularly like Figure 4, it shows how to train the networks. I found reading this paper very slowly a few times to give me a much firmer understanding of variational autoencoders.

## [Early Visual Concept Learning with Unsupervised Deep Learning](http://arxiv.org/pdf/1606.05579v1.pdf) (Jun 17, 2016)

Looks at disantagleing variables of the learned latent space of variational autoencoders. Often times in varaitional autoencoders some of the variables tend to never be used. This is sometimes called the componet collapse problem. Before I read this paper I thought this was a undisirable trait however they argue that it is adventagous in some tasks because it builds better more independent features. They report a trade off between reconstruction accuracy and ability to disantagle variables. Their whole approach reliys on a tempeture coefficient Beta on the VAE loss.

## [Variational Autoencoders (VAE) vs Generative Adversarial Networks (GAN)](https://www.reddit.com/r/MachineLearning/comments/4r3pjy/variational_autoencoders_vae_vs_generative/) (Jul 3, 2016)

So many great sources are on this page.

## [what loss to use for variational auto encoder with real numbers](https://www.reddit.com/r/MachineLearning/comments/4ujr2s/what_loss_to_use_for_variational_auto_encoder/) (Jul 25, 2016)

Seeing this 2 months ago would have saved me a lot of time. I found it rediculously difficult to train variational autoencoders with L2 loss. I gave up eventualy and just used log loss and normalized my data between 0 and 1. There is a commit about using Huber loss instead of L2 to speed things up. After trying it I noticed similar speed increases in training.

## [Generating Sentences from a Continuous Space](https://arxiv.org/pdf/1511.06349.pdf)

Does like a Seq2Seq type thing but the hidden state is treated as latent space right before decoding. Figure 1 says it all. Looks like a super good method. I would like to try it out.

## [Auto-Encoding Variational Bayes](http://arxiv.org/pdf/1312.6114.pdf) (May 1, 2014)

Ya, I guess I will put the original paper in this list.

# Inception Network






