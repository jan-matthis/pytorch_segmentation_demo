# U-Net in PyTorch

Implemenation of a basic U-Net architecture for segmentation in PyTorch. 


## Package requirements

If you want to execute the notebook, make sure that you have the following packages installed (e.g. using `pip` or `conda`):
- PyTorch, see http://pytorch.org/
- tqdm, a progress bar module, see https://github.com/tqdm/tqdm#installation


## Dataset

As an example dataset, we use retinal images from the [DRIVE database](http://www.isi.uu.nl/Research/Databases/DRIVE/), which can be downloaded via: http://www.isi.uu.nl/Research/Databases/DRIVE/download.php

Extract the dataset to the subfolder `datasets/drive/DRIVE_SRC/`. Then run the `prepare.py` script from `dataset/drive/` once.
