## Awesome Data-Efficient ViT (Vision Transformer)

### 1. **Why data-efficient vision transformer?**

Data-hungry property of Vision Transformer (ViT) hinders it from widespread application on various data scarcity sceneries. 

We collect a paper list for data-efficient training methods as follows.

The contributions of data-efficient ViT are welcomed.



### 2. Paper List

+ **Data-Efficient Multi-Scale Fusion Vision Transformer**

  [[link](https://www.sciencedirect.com/science/article/pii/S0031320324010562 )], [[code](https://github.com/visresearch/dems)], [2025]
> TLDR: incorporate multi-scale vision tokens to improve data efficiency for the training of vision transformer. 
>
> data-efficient training on CIFAR10, CIFAR100, EMNIST, Fashion-MNIST and Caltech101 dataset.

+ **Multi-Grained Contrast for Data-Efficient Unsupervised Representation Learning**

  [[arxiv](https://arxiv.org/abs/2407.02014)], [[code](https://github.com/visresearch/mgc)], [2024]
> TLDR: construct multi-grained correspondences between positive views for contrastive learning to capture the representations of different granularity semantics. 
>
> data-efficient training on COCO, PASCAL VOC and ADE20K dataset.

+ **Inter-Instance Similarity Modeling for Contrastive Learning**

  [[arxiv](https://arxiv.org/abs/2306.12243 )], [[code](https://github.com/visresearch/patchmix)], [2023]
> TLDR: construct inter-instance similarity between different image instance by patch-mix strategy to encourage the model to capture the similarity between natural images. 
>
> data-efficient training on CIFAR10 and CIFAR100 dataset.

+ **Asymmetric Patch Sampling for Contrastive Learning**

  [[link](https://www.sciencedirect.com/science/article/pii/S0031320324007635 )], [[arxiv](https://arxiv.org/abs/2306.02854)], [[code](https://github.com/visresearch/aps)], [2025]
> TLDR: construct hard positive pairs to encourage more appearance-invariant representations.
>
> data-efficient training on CIFAR10 and CIFAR100 dataset.
