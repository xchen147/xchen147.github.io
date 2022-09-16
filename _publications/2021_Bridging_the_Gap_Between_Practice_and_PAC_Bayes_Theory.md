---
title: "Bridging the Gap Between Practice and PAC-Bayes Theory in Few-Shot Meta-Learning"
collection: publications
permalink: /publication/2021_Bridging_the_Gap_Between_Practice_and_PAC_Bayes_Theory
excerpt: 'We develop two PAC-Bayesian bounds tailored for the few-shot learning setting and show that two existing meta-learning algorithms (MAML and Reptile) can be derived from our bounds, thereby bridging the gap between practice and PAC-Bayesian theories.'
date: 2021
author: '*Nan Ding, **Xi Chen**, Tomer Levinboim, Sebastian Goodman, Radu Soricut*' 
venue: 'NeurIPS 2021'
paperurl: 'https://proceedings.neurips.cc/paper/2021/hash/f6b6d2a114a9644419dc8d2315f22401-Abstract.html'

---

Despite recent advances in its theoretical understanding, there still remains a significant gap in the ability of existing PAC-Bayesian theories on meta-learning to explain performance improvements in the few-shot learning setting, where the number of training examples in the target tasks is severely limited. This gap originates from an assumption in the existing theories which supposes that the number of training examples in the observed tasks and the number of training examples in the target tasks follow the same distribution, an assumption that rarely holds in practice. By relaxing this assumption, we develop two PAC-Bayesian bounds tailored for the few-shot learning setting and show that two existing meta-learning algorithms (MAML and Reptile) can be derived from our bounds, thereby bridging the gap between practice and PAC-Bayesian theories. Furthermore, we derive a new computationally-efficient PACMAML algorithm, and show it outperforms existing meta-learning algorithms on several few-shot benchmark datasets.

[Access the paper here]([https://arxiv.org/abs/2203.05126](https://proceedings.neurips.cc/paper/2021/hash/f6b6d2a114a9644419dc8d2315f22401-Abstract.html))
