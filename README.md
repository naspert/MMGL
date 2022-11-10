# Multi-modal Graph learning for Disease Prediction (MMGL)

This is a PyTorch transductive version of the MMGL model as proposed in our paper, the inductive version will be coming soon.

## Introduction
We hope MMGL as a flexible baseline could help you to explore more powerful variants and perform scenario-specific multi-modal adaptive graph learning for more biomedical tasks. In this work, we propose an end-to-end Multi-modal Graph Learning framework (MMGL) for disease prediction with multi-modality. To effectively exploit the rich information across multi-modality associated with the disease, modality-aware representation learning is proposed to aggregate the features of each modality by leveraging the correlation and complementarity between the modalities. Furthermore, instead of defining the graph manually, the latent graph structure is captured through an effective way of adaptive graph learning. It could be jointly optimized with the prediction model, thus revealing the intrinsic connections among samples. Our model is also applicable to the scenario of inductive learning for those unseen data.

For more details about MMGL, please refer to our paper [[TMI](https://ieeexplore.ieee.org/abstract/document/9733917)] [[Arxiv](https://arxiv.org/abs/2203.05880)].
![image](https://github.com/SsGood/MMGL/blob/main/img/MMGL.png)

## Requirements
* PyTorch >= 1.1.0
* python 3.6
* networkx
* scikit-learn
* scipy
* munkres

## Code running

Please refer to  [[./MMGL/README.md](https://github.com/SsGood/MMGL/blob/main/MMGL/README.md)]

## Data

If you want to use your own data, you have to provide 
* a csv.file which contains multi-modal features, and
* a multi-modal feature dict.

