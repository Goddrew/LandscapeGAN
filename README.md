# LandscapeGAN

## About 
This project aims to generate landscape images using the GAN architecture. This GAN that I re-implemented is trained on [Landscape Pictures](https://www.kaggle.com/datasets/arnaud58/landscape-pictures) (around 4300 landscape images). The model is built using PyTorch. 

## Training Process & Result 
The learning rate I used is `0.0001` with beta1 value of `0.5`. The model is trained with 50 epochs. However the performance is not that great. My model seems to suffer from mode collapse. Furthermore, the generator is not learning that well. 

## Future Work
Collecting and increasing the dataset size to help with mode collapse and might look into other architecture alternatives. 

## Acknowledgements 
Current model inspired from 
1. [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)   