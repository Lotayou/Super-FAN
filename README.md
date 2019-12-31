# FSRNet Pytorch
The PyTorch implement of Super-FAN.
[Super-FAN: Integrated facial landmark localization and super-resolution of real-world low resolution faces in arbitrary poses with GANs](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bulat_Super-FAN_Integrated_Facial_CVPR_2018_paper.pdf)
Based on [SRGAN](https://github.com/leftthomas/SRGAN), I altered the code by adopting Super-FAN network structure. 

## Prerequisites

* Python 3.6
* Pytorch 1.0 or newer

## Train

Use the same dataset of [FSRNet](https://github.com/cydiachen/FSRNET_pytorch).Change the option in Train.py to set the dataset's directory. I am using CelebAHQ-MASK as the training set. The GroundTruth is generated by zllrunning/face-parsing.PyTorch(https://github.com/zllrunning/face-parsing.PyTorch) with pretrained model.

Dataset Link: https://pan.baidu.com/s/1HEECUyKI5GOSrd7NPlm-ow  密码:z2ud

## Test

TODO:  Upload the pretrain model to BaiduDisk