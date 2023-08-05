# MSD_medical_segmentation
## Application of UNet to the hippocampus segmentation task of the Medical Segmentation Decathlon (MSD) challenge.

The Medical Segmentation Decathlon (MSD - Antonelli et al., 2022) is an international machine learning challenge focused on developing a general-purpose algorithm for medical image segmentation. It comprises ten different datasets with various challenging characteristics, aiming to test the generalizability of algorithms across multiple semantic segmentation tasks in healthcare.

This repo contains a .ipynb notebook built to flexibly experiment with different neural networks, data processing and training settings, in the context of this challenge.

For the scope, three libraries from the PyTorch Ecosystem are leveraged: TorchIO was used for data loading, preprocessing and augmentation. MONAI provided network, loss function and metric. 
Finally, the high-level framework PyTorch Lightning was used for training and data modules.

As an exemplary application, UNet is trained on the hippocampus segmentation task.
