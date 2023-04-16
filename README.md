# UofM EECS 351 p2GAN Implementation
For Neural Style Transfer: https://github.com/ziyang-ning/Neural_Style_Transfer

## Sources & Authors
Based on Paper linked: https://arxiv.org/abs/2001.07466 

Original Author: Zhentan Zheng, Jianyi Liu

Original Code: https://github.com/i-evi/p2gan

Editor: Jason Ning

The original code was written in TensorFlow 1.X and was a python script. I have edited the code to work with TensorFlow 2 and made it into a python notebook file for easy use/access. 

I do not own any of the code. Please contact me if this repository needs to be removed. This project was for learning purposes only.

## Purpose
Compare GAN style transfer with Neural Style Transfer

Learn TensorFlow and Singal Processing techniques

## Dependencies
Anaconda TensorFlow 2: `conda install tensorflow-gpu` for Windows

OpenCV2: `pip install opencv-python`


For Mac instructions: https://github.com/jeffheaton/t81_558_deep_learning/blob/master/install/tensorflow-install-mac-metal-jan-2023.ipynb

Import NoteBook: `pip install import-ipynb`

TF_Slim: `pip install --upgrade tf_slim`

You can also use conda install for the commands used above.

Download VGG (second link) in the same directory as everything else:
https://mega.nz/#!YU1FWJrA!O1ywiCS2IiOlUCtCpI6HTJOMrneN-Qdv3ywQP5poecM

(from this https://github.com/machrisaa/tensorflow-vgg)

## How to Use
Modify the `train.ipynb` for training a new model

Run the `render.ipynb` for rendering new images with a specific model

For more on what the parameters do, please check out the original code repo.



