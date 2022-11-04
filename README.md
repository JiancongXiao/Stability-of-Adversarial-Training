# Stability Analysis and Generalization Bounds of Adversarial Training

**Jiancong Xiao, Yanbo Fan, Ruoyu Sun, Jue Wang, Zhi-Quan Luo**

**arXiv:** [https://arxiv.org/abs/2210.00960](https://arxiv.org/abs/2210.00960) 

**Openreview:** [https://openreview.net/forum?id=78aj7sPX4s-](https://openreview.net/forum?id=78aj7sPX4s-)

NeurIPS 2022

## Abstract

In adversarial machine learning, deep neural networks can fit the adversarial examples on the training dataset but have poor generalization ability on the test set. This phenomenon is called robust overfitting, and it can be observed when adversarially training neural nets on common datasets, including SVHN, CIFAR-10, CIFAR-100, and ImageNet. In this paper, we study the robust overfitting issue of adversarial training by using tools from uniform stability. One major challenge is that the outer function (as a maximization of the inner function) is nonsmooth, so the standard technique (e.g., Hardt et al., 2016) cannot be applied. Our approach is to consider $\eta$-approximate smoothness: we show that the outer function satisfies this modified smoothness assumption with $\eta$ being a constant related to the adversarial perturbation $\epsilon$. Based on this, we derive stability-based generalization bounds for stochastic gradient descent (SGD) on the general class of $\eta$-approximate smooth functions, which covers the adversarial loss. Our results suggest that robust test accuracy decreases in $\epsilon$ when $T$ is large, with a speed between $\Omega(\epsilon\sqrt{T})$ and $\mathcal{O}(\epsilon T)$. This phenomenon is also observed in practice. Additionally, we show that a few popular techniques for adversarial training (\emph{e.g.,} early stopping, cyclic learning rate, and stochastic weight averaging) are stability-promoting in theory.


## Code

 This is a mainly theoretical paper. The code is adopted from the experiments of [Rice et al., 2020](https://github.com/locuslab/robust_overfitting).
 

## Citation
```
@inproceedings{
xiao2022stability,
title={Stability Analysis and Generalization Bounds of Adversarial Training},
author={Jiancong Xiao and Yanbo Fan and Ruoyu Sun and Jue Wang and Zhi-Quan Luo},
booktitle={Advances in Neural Information Processing Systems},
editor={Alice H. Oh and Alekh Agarwal and Danielle Belgrave and Kyunghyun Cho},
year={2022},
url={https://openreview.net/forum?id=78aj7sPX4s-}
}
```
