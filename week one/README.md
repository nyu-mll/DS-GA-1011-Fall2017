Lab 1
=====

## Overview

In this lab, we will be going over the basics of PyTorch. If you have already used PyTorch extensively feel free to skip this session.

Lecture & Lab 1 overview: <https://docs.google.com/a/nyu.edu/document/d/1AniFu--SRFn0IN8IbxllsRS53-Asrr14_7ZFISXILso/edit?usp=sharing>

## Setup

Please have Anaconda with Python 3.6 installed prior to the first class.
We will be using Jupyter Notebooks and PyTorch for this course; these can easily be installed with conda:
- `conda install jupyter`
- `conda install pytorch torchvision -c soumith`

- If you have Jupyter installed outside of your conda environment, you may need to install it again to ensure that your conda packages are available within the notebook.
- pip installation is also an option, but Anaconda is strongly recommended.

You will also need matplotlib for this lab.
- `conda install matplotlib`

## Introduction to PyTorch Tensors

Please read and complete the exercises in `tensor_tutorial.ipynb`. This tutorial goes over the tensor operations in PyTorch - they are very similar to those in numpy. The tensor operation section is the most part of the lab to understand.

## Introduction to Autograd (Time Permitting)

If you have time, read and complete the exercises in `autograd_tutorial.ipynb`. This tutorial introduces the automatic differentiation feature of PyTorch and has several demos involving linear and logistic regression. Autograd is important to understand, but will be covered more extensively in future lectures and labs. 

## Credits
This tutorial is based on the following tutorials:
- http://pytorch.org/tutorials/
- https://github.com/yunjey/pytorch-tutorial
- Jake Zhao's Deep Learning Spring 2017 PyTorch Tutorial
