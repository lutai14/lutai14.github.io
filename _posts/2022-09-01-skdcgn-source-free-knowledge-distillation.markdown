---
title: ":memo: SKDCGN: Source-free Knowledge Distillation of Counterfactual Generative Networks using cGANs"
layout: post
date: 2022-09-01
#tag: fairness
headerImage: false
projects: true
hidden: false # don't count this post in blog pagination
description: "SKDCGN: Source-free Knowledge Distillation of Counterfactual Generative Networks using cGANs"
category: project
author: matteotafuro
externalLink: false
---

\[[Paper](https://arxiv.org/abs/2208.04226){:target="_blank"}\] \[[Code](https://github.com/ambekarsameer96/SKDCGN){:target="_blank"}\]

*Abstract: With the usage of appropriate inductive biases, Counterfactual Generative Networks (CGNs) can generate novel images from random combinations of shape, texture, and background manifolds. These images can be utilized to train an invariant classifier, avoiding the wide spread problem of deep architectures learning spurious correlations rather than meaningful ones. As a consequence, out-of-domain robustness is improved. However, the CGN architecture comprises multiple over parameterized networks, namely BigGAN and U2-Net. Training these networks requires appropriate background knowledge and extensive computation. Since one does not always have access to the precise training details, nor do they always possess the necessary knowledge of counterfactuals, our work addresses the following question: Can we use the knowledge embedded in pre-trained CGNs to train a lower-capacity model, assuming black-box access (i.e., only access to the pretrained CGN model) to the components of the architecture? In this direction, we propose a novel work named SKDCGN that attempts knowledge transfer using Knowledge Distillation (KD). In our proposed architecture, each independent mechanism (shape, texture, background) is represented by a student ’TinyGAN’ that learns from the pretrained teacher ’BigGAN’. We demonstrate the efficacy of the proposed method using state-of-the-art datasets such as ImageNet, and MNIST by using KD and appropriate loss functions. Moreover, as an additional contribution, our paper conducts a thorough study on the composition mechanism of the CGNs, to gain a better understanding of how each mechanism influences the classification accuracy of an invariant classifier.*

