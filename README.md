# Vision-Transformer-using-PyTorch-and-Tensorboard

## Introduction to the code
This GitHub repository provides PyTorch implementation of ViT.
I created this code by referencing this blog.
https://csm-kr.tistory.com/54

## Modifications
I added code so that users can visualize the training results using Tensorboard.
I also tried optimizing the code. I made a modifications in line 141~142.
This modification speeds up the training process and saves computations.

## Dataset
The original code uses CIFAR10. And this code also uses CIFAR10.

## How-to-run
In order to use the code. Use the following code.
python ./ViT_practice.py

## Addressing Issues
If you encounder issues, try installing the modules required to run the code.

## Results
The results are provided below.
This is the graph of the validation accuracy from epoch 1~50.
![ViT val acc](https://github.com/parkie0517/Vision-Transformer-using-PyTorch-and-Tensorboard/assets/80407632/9cdf9357-26db-4c78-ab80-c381bda80d7c)

This is the graph of the validation loss from epoch 1~50.
![ViT val loss](https://github.com/parkie0517/Vision-Transformer-using-PyTorch-and-Tensorboard/assets/80407632/6faba62d-563f-41ef-9390-b910504ee556)
