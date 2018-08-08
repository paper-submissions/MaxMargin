# The Implicit Bias of Gradient Descent on Separable Data


PyTorch implementation of the empirical results described in ["The Implicit Bias of Gradient Descent on Separable Data"](https://arxiv.org/abs/1710.10345) (ICLR-2018) by Daniel Soudry, Elad Hoffer, Mor Shpigel Nacson, Suriya Gunasekar, Nathan Srebro.

```
@inproceedings{
soudry2018the,
title={The Implicit Bias of Gradient Descent on Separable Data},
author={Daniel Soudry and Elad Hoffer and Nathan Srebro},
booktitle={International Conference on Learning Representations},
year={2018},
url={https://openreview.net/forum?id=r1q7n9gAb},
}
```

## Running Resnet44-cifar10 example
To get the relevant figures simply run
```
python main.py --save maxmargin_results
```

## Dependencies

- [pytorch](<http://www.pytorch.org>)
- [torchvision](<https://github.com/pytorch/vision>) to load the datasets, perform image transforms
- [pandas](<http://pandas.pydata.org/>) for logging to csv
- [bokeh](<http://bokeh.pydata.org>) for training visualization


## Data
- Configure your dataset path at **data.py**.