# Training for the Decathlon :mag::brain:
## Application of UNet to the hippocampus segmentation task of the Medical Segmentation Decathlon (MSD) challenge.

The Medical Segmentation Decathlon (MSD - [Antonelli et al., 2022](https://www.nature.com/articles/s41467-022-30695-9)) is an international machine-learning challenge focused on developing a general-purpose algorithm for medical image segmentation. It comprises ten different datasets of medical images collected with different modalities (MRI, mp-MRI, CT) from different organs, aiming to test the generalizability of algorithms across multiple semantic segmentation tasks in healthcare.

This repo contains a jupyter notebook built to flexibly experiment with different neural networks, data processing and training settings, in the context of this challenge.

For the scope, three libraries from the PyTorch Ecosystem are leveraged: [TorchIO](https://torchio.readthedocs.io/) is used for data loading, preprocessing and augmentation. [MONAI](https://docs.monai.io/en/stable/) provides network, loss function and metric. 
Finally, the high-level framework [PyTorch Lightning](https://lightning.ai/docs/pytorch/stable/) is used for training and data module.

As an exemplary application, UNet is trained on the hippocampus segmentation task.
