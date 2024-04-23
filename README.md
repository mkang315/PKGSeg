# Official MCTSeg
This is the source code for the paper, "A Multimodal Feature Distillation with CNN-Transformer Network for Brain Tumor Segmentation with Incomplete Modalities", of which I am the first author.

## Model
The model configuration (i.e., network construction) file is net.py in the directory .\model.
To train and test by running train.py and test.py.

## Evaluation
Datasets Brain Tumor Segmentation (BraTS) Challenge 2018/2020 ([BraTS2018](https://www.med.upenn.edu/sbia/brats2018.html)/[BraTS2020](https://www.med.upenn.edu/cbica/brats2020/)).

## Suggested Citation
Our manuscript has been uploaded on [arXiv](https://arxiv.org/abs/2404.14019). Please cite our paper if you use code from this repository:
> Plain Text

- *IEEE* Style</br>
M. Kang, F. F. Ting, R. C.-W. Phan, Z. Ge, and C.-M. Ting, "A multimodal feature distillation with cnn-transformer network for brain tumor segmentation with incomplete modalities," arXiv:2404.14019 [cs.CV], Apr. 2024.</br>

- *Nature* Style</br>
Kang, M., Ting, F. F., Phan, R. C.-W., Ge, Z, & Ting, C.-M.. A multimodal feature distillation with CNN-Transformer network for brain tumor segmentation with incomplete modalities. Preprint at https://arxiv.org/abs/2404.14019 (2024).</br>

- *Springer* Style</br>
Kang, M., Ting, F. F., Phan, R.C.-W., Ge, Z., Ting, C.-M.: A multimodal feature distillation with cnn-transformer network for brain tumor segmentation with incomplete modalities. arXiv preprint [arXiv:2404.14019](https://arxiv.org/abs/2404.14019) (2024)</br>

## License
PKGSeg is released under the BSD 3-Clause "New" or "Revised" License. Please see the [LICENSE](https://github.com/mkang315/PKGSeg/blob/main/LICENSE) file for more information.

## Copyright Notice
Many utility codes of our project base on the codes of [PyTorch-3DUNet](https://github.com/wolny/pytorch-3dunet), [mmFormer](https://github.com/YaoZhang93/mmFormer), [Vision Transformer PyTorch](https://github.com/asyml/vision-transformer-pytorch), and [Factor-Transfer-pytorch](https://github.com/Jangho-Kim/Factor-Transfer-pytorch) repositories.
