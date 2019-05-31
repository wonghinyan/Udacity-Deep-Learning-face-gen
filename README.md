# Face Generation using DCGAN #
Project coursework as part of Udacity Deep Learning course

This application uses a DCGAN neural network that learns from a data set of faces in order to generate new faces. The dataset comes from [CelebFaces Attributes Dataset (celebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) - upon which the adversarial network will train. This application goes through the following steps:
1. Pre-process the data downloaded from CelebA by cropping and resizing to 64x64x3
2. Create a dataloader for the data to be processed
3. Define the DCGAN model, which includes a Generator and a Discriminator
4. Train the neural network
5. Generate new faces

A number of different [optimizers from PyTorch](https://pytorch.org/docs/stable/optim.html) were used to compare network performance. The Jupyter notebook includes results from these experimentations. 

Generated faces are shown towards the end of the notebook. Some look more realistic than others. 

Requirements:
- Python 3
- Pytorch
- Numpy
- Panda
- matplotlib
- Pickle
