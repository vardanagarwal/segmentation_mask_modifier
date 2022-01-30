# seg_mask_modifs

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fvardanagarwal%2Fmask_modifs&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## Description
A package for easy generation of mask of different labels using multiple models and applying different operations on that.

#### Curent models and labels supported:
- Deeplabv3 with pascal labels
- Maskrcnn with coco labels
- Bisnet with face labels

## Usage

### Installation
pip:
```
pip install seg-mask-modifs
```

Install the requirements from requirements.txt
```
pip install -r requirements.txt
```

## References
Face parsing: https://github.com/zllrunning/face-parsing.PyTorch
Mask-RCNN: https://pytorch.org/vision/stable/_modules/torchvision/models/detection/mask_rcnn.html
Deeplabv3: https://pytorch.org/vision/main/_modules/torchvision/models/segmentation/deeplabv3.html
