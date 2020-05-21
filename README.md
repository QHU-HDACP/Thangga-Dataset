## Licence
Please notice that this dataset is made available for academic research purpose only. All the images are collected from the Internet, and the copyright belongs to the original owners. If any of the images belongs to you and you would like it removed, please kindly inform us, we will remove it from our dataset immediately.

## Data overview
We are making available a large newly collected dataset -**Thangga**- of **RGB** images with a large diversity of contents.

The Thangga dataset is divided into:
- train data: starting from 746 high definition high resolution images we obtain corresponding low resolution images and provide both high and low resolution images for 2, 3, and 4 downscaling factors.

- validation data: 100 high definition high resolution images are used for genereting low resolution corresponding images.

- test data: 100 diverse images are used to generate low resolution corresponding images.

## Data structure
Thangka dataset has the following structure:
946 images divided into: 746 images for training, 100 images for validation, 100 images for testing.

Thangga forder structure is as follows:
`Thangga/` -- Thangka dataset

### Train Dataset
`Thangga/train/Thangga_train_HR/`--0001.png, 0002.png, ..., 0746.png train HR images (provided to the participants)

`Thangga/train/Thangga_train_LR_bicubic/`--corresponding low resolution images obtained using Python imresize function with default settings (bicubic interpolation)

`Thangga/train/Thangga_train_LR_bicubic/X2/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x2

`Thangga/train/Thangga_train_LR_bicubic/X3/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x3

`Thangga/train/Thangga_train_LR_bicubic/X4/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x4

`Thangga/train/Thangga_train_LR/`-- corresponding low resolution images

`Thangga/train/Thangga_train_LR/X2/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x2

`Thangga/train/Thangga_train_LR/X3/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x3

`Thangga/train/Thangga_train_LR/X4/`--0001.png, 0002.png, ..., 0746.png train LR images, downscale factor x4

### Valid Dataset

`Thangga/valid/Thangga_valid_HR/`--001.png, 002.png, ..., 100.png validation HR images (will be available to the participants at the beginning of the final evaluation phase)

`Thangga/valid/Thangga_valid_LR_bicubic/`-- corresponding low resolution images obtained using Matlab imresize function with default settings (bicubic interpolation)

`Thangga/valid/Thangga_valid_LR_bicubic/X2/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x2

`Thangga/valid/Thangga_valid_LR_bicubic/X3/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x3

`Thangga/valid/Thangga_valid_LR_bicubic/X4/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x4

`Thangga/valid/Thangga_valid_LR/`-- corresponding low resolution images

`Thangga/valid/Thangga_valid_LR/X2/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x2

`Thangga//valid/Thangga_valid_LR/X3/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x3

`Thangga/valid/Thangga_valid_LR/X4/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x4

### Test Dataset

`Thangga/test/Thangga_test_HR/`--001.png, 002.png, ..., 100.png test HR images (not provided to the participants, used for final evaluation and ranking)

`Thangga/test/Thangga_test_LR_bicubic/`-- corresponding low resolution images obtained using Matlab imresize function with default settings (bicubic interpolation)

`Thangga/test/Thangga_test_LR_bicubic/X2/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x2

`Thangga/test/Thangga_test_LR_bicubic/X3/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x3

`Thangga/test/Thangga_test_LR_bicubic/X4/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x4

`Thangga/test/Thangga_test_LR/`-- corresponding low resolution images

`Thangga/test/Thangga_test_LR/X2/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x2

`Thangga/test/Thangga_test_LR/X3/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x3

`Thangga/test/Thangga_test_LR/X4/`--001.png, 002.png, ..., 100.png train LR images, downscale factor x4

## Download Link

1. [Baidu Driver：https://pan.baidu.com/s/1SbRoNjf_BJLXamaTkxLPYg, Password：og5e](https://pan.baidu.com/s/1SbRoNjf_BJLXamaTkxLPYg)

2. [Google Driver](https://drive.google.com/drive/folders/1nC46katNxgU_eLLtE2dyiCTvz6wVVXLH?usp=sharing)


## Citing Thangga Dataset

If you find Thangga Dataset useful, please cite it in your publications.

```latex
@misc{thangga,
  author = {Kai Li, Xiaohan Huang, Zongyuan Li, Jianqiang Huang, Xiaoying Wang},
  title = {Thangga-Dataset},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/QHU-HDACP/Thangga-Dataset}},
}
```
