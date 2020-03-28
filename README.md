# Medical Zoo Pytorch
Our goal is to implementent an open-source medical image segmentation library of state of the art 3D deep neural networks in PyTorch along with data loaders of the most common medical MRI datasets. The first stable release of our repository is almost ready.

We strongly believe in open and **reproducible deep learning research**.
In order to reproduce our results, the code and materials of this work are available in this repository.

This project started as an MSc Thesis and is currently under further development. For 3D multi-modal brain MRI segmentation check the thesis branch of this repository.

## Beta release - work in progress!
Although this work was initially focused on **3D multi-modal brain MRI segmentation** we will slowly add more architectures and dataloaders.

## New released cool features (03/2020)

1. Batch size training support
2. On the fly volume vizualization
3. Tensorboard and PyTorch 1.4 support to track training progress
3. Code cleanup and package creation
4. Offline sub-volume generation 
5. Add hyperdensenet and 3dresnet-vae
6. Fix mrbrains dataloader

## Top priorities

1. Fix Brats2018 dataloaders
2. Add hyper densenet and other architectures
3. Save produced 3d-segmenentation as medical images 

## Implemented dataloaders
[Iseg 2017](http://iseg2017.web.unc.edu/ "Official iseg-2017 dataset page")

[Mrbrains 2018](https://mrbrains18.isi.uu.nl/ "Mrbrains 2018 official website")

## Implemented architectures
[Densenet3D](https://arxiv.org/abs/1804.02967)
[Unet3D](https://arxiv.org/abs/1606.06650)
[Vnet](https://arxiv.org/abs/1606.04797)
[Hyperdensenet](https://arxiv.org/abs/1804.02967)
[ResNet3D-VAE](https://arxiv.org/pdf/1810.11654.pdf)

## Results
#### To be updated **really really** soon......

|   | iseg-2017  | mrbrains-2018 (4 classes)   | mrbrains-2018 (8 classes)  | 
|---|---|---|---|---|
| 3D-Unet  | 93.84   | 89.02   | ...   | 



## Documentation
Check installation folder for instructions. To be updated...

## Our current team
### [Ilias Papastatis](https://github.com/IliasPap "Git page" )
### [Nikolas Adaloglou](https://www.linkedin.com/in/adaloglou17/ "LinkedIn page")

## Support 
If you **really** like this repository and find it useful, please consider (★) **starring** it, so that it can reach a broader audience of like-minded people.
