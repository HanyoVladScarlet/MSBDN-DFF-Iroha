# MSBDN-DFF
The source code of CVPR 2020 paper **"Multi-Scale Boosted Dehazing Network with Dense Feature Fusion"** by  [Hang Dong](https://sites.google.com/view/hdong/%E9%A6%96%E9%A1%B5), [Jinshan Pan](https://jspan.github.io/), Xiang Lei, [Zhe Hu](https://zjuela.github.io/), [Xinyi Zhang](http://xinyizhang.tech), Fei Wang, [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/)

## Dependencies
* Python 3.6
* PyTorch >= 1.1.0
* torchvision
* numpy
* skimage
* h5py
* MATLAB

## Test
1. Download the [Pretrained model on RESIDE](https://drive.google.com/open?id=1da13IOlJ3FQfH6Duj_u1exmZzgXPaYXe) and
[Test set](https://drive.google.com/open?id=1qZlnJN4ybjunc2BGh6kjOUfFdVxuNS-P) to  ``MSBDN-DFF/models`` and ``MSBDN-DFF/``folder, respectively.

2. Run the ``MSBDN-DFF/test.py`` with cuda on command line: 
```bash
MSBDN-DFF/$python test.py --checkpoint path_to_pretrained_model --dataset
```

3.The dehazed images will be saved in the directory of the test set.

## Train
The training scripts will be coming soon.

## Citation

If you use these models in your research, please cite:

	@conference{MSBDN-DFF,
		author = {Hang, Dong and Jinshan, Pan and Xiang, Lei ans Zhe, Hu and Fei, Wang and Ming-Hsuan, Yang},
		title = {Multi-Scale Boosted Dehazing Network with Dense Feature Fusion},
		booktitle = {CVPR},
		year = {2020}
	}
