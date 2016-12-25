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

## [Generating Sentences from a Continuous Space](https://arxiv.org/pdf/1511.06349.pdf) (May 12, 2016)

Does like a Seq2Seq type thing but the hidden state is treated as latent space right before decoding. Figure 1 says it all. Looks like a super good method. I would like to try it out.

## [Auto-Encoding Variational Bayes](http://arxiv.org/pdf/1312.6114.pdf) (May 1, 2014)

Ya, I guess I will put the original paper in this list.

## [Embed to Control: A Locally Linear Latent Dynamics Model for Control from Raw Images](https://arxiv.org/pdf/1506.07365v3.pdf) (Nov 20, 2015)

Use variational autoencoders to learn compressed representations of control type problems. Figure 1 says it all really. Basicly they learn a linear mapping on the latent space encodeing and use this for planning. They apply it to some basic reinforcement learning problems with visual input.

# Inception Network

## [Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567) (Dec 11, 2015)

## [Going deeper with convolutions](https://arxiv.org/pdf/1409.4842v1.pdf) (Sep 17, 2014)

# Physics Simulations with Neural Networks

## [Accelerating Eulerian Fluid Simulation with Convolutional Networks](https://arxiv.org/pdf/1607.03597v2.pdf) (Jul 14, 2016)

## [Convolutional Neural Networks for Steady Flow Approximation](http://delivery.acm.org/10.1145/2940000/2939738/p481-guo.pdf?ip=159.16.89.60&id=2939738&acc=ACTIVE%20SERVICE&key=6F4CCF05E2930152.3A406A232738A87B.4D4702B0C3E38B35.4D4702B0C3E38B35&CFID=669259551&CFTOKEN=29446944&__acm__=1474220024_73e2d939e30a8b3f8dfcbace50676e17) (Aug 16, 2016)

# ResNet

## [Wide Residual Networks](https://arxiv.org/pdf/1605.07146v1.pdf) (May 23, 2016)

# Transfer Learning

## [Net2Net: Accelerating Learning via Knowledge Transfer](https://arxiv.org/abs/1511.05641) (Apr 23, 2016)

# Super Resolution

## [Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network] (http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Shi_Real-Time_Single_Image_CVPR_2016_paper.pdf) (Sep 23, 2016)

## [Image Super-Resolution Using Deep Convolutional Networks](https://arxiv.org/pdf/1501.00092.pdf) (Jul 31, 2015)

# Video Prediction

## [Deep Mulit-Scale Video Prediction Beyond Mean Square Error](https://arxiv.org/pdf/1511.05440v6.pdf) (Feb 26, 2016)

## [Action-Conditional Video Prediction using Deep Networks in Atari Games](http://web.eecs.umich.edu/~baveja/Papers/NIPS2015.pdf)

## [LEARNING VISUAL PREDICTIVE MODELS OF PHYSICS FOR PLAYING BILLIARDS](https://arxiv.org/pdf/1511.07404.pdf) (Jan 19, 2016)

## [Deep Predictive Coding Networks for Video Prediction and Unsupervised Learning](https://arxiv.org/pdf/1605.08104.pdf) (Aug 31, 2016)

# Neural Networks for Artistic Style

## [Semantic Style Transfer and Turning Two-Bit Doodles into Fine Artwork](https://arxiv.org/pdf/1603.01768v1.pdf) (Mar 5, 2016)

## [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf) (Sep 2, 2015)

# Cool Papers

## [UNDERSTANDING DEEP LEARNING REQUIRES RETHINKING GENERALIZATION](https://openreview.net/pdf?id=Sy8gdB9xx) (ICLR 2017)



