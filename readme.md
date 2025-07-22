# Dependencies

* Python 3 (Recommend to use [Anaconda](https://www.anaconda.com/distribution/#linux))
* [Pytorch 1.0.1](https://pytorch.org/)
* NVIDIA GPU + [CUDA](https://developer.nvidia.com/cuda-downloads)
* Python packages: pip install opencv-python, visdom

## Train

1. Modify the configuration file  `options/train/train_sr.json`
2. Run command: `python train.py -opt options/train/train_sr.json`

*Note that: `using_spanet_dadaset = True` to use SPANet dataset for training*

## Testing

1. Modify the configuration file `options/test/test_sr.json` 
1. Run command: `python test.py -opt options/test/test_sr.json`