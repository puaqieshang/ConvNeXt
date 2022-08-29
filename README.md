# ConvNeXt, with a Non-Local Block

We propose a PyTorch implementation of **ConvNeXt**, with a Non-Local Block.

The base model, ConvNeXt, is based on the the following paper:

[A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545)
[[`arXiv`](https://arxiv.org/abs/2201.03545)][[`video`](https://www.youtube.com/watch?v=QzCjXqFnWPE)]

On the other hand, Non-Local Neural Networks are based on the following paper:

[Non-local Neural Networks](https://arxiv.org/abs/1711.07971)
[[`arXiv`](https://arxiv.org/abs/1711.07971)]

This repository combines the best of both worlds to achieve a superior accuracy in classifying lung diseases (lung cancer, Covid-19, pneumonia) from Chest X-Rays images. 

--- 

<p align="center">
<img src="https://user-images.githubusercontent.com/8370623/180626875-fe958128-6102-4f01-9ca4-e3a30c3148f9.png" width=100% height=100% 
class="center">
</p>

## Acknowledgement
This repository is built using the [timm](https://github.com/rwightman/pytorch-image-models) library, [DeiT](https://github.com/facebookresearch/deit), [tea1528](https://github.com/tea1528/Non-Local-NN-Pytorch) and [BEiT](https://github.com/microsoft/unilm/tree/master/beit) repositories.

## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE) file for more information.
