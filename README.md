### Neural Style Transfer in audio domains

This is an implementation of Neural Style Transfer from the paper <a href="https://arxiv.org/abs/1710.11385">Audio Style Transfer</a> in Keras 2.0+

### Colaboratory Support
[This codebase can now be run directly from colaboratory using the following link](https://colab.research.google.com/github/ccsusan/nst4audio/), or by opening `NeuralStyleTransfer.ipynb` and visiting the Colab link.

**NOTE :** Make sure you use a GPU in Colab. To change Runtimes : `Runtime -> Change Runtime type ->`. Here select Python 3 and GPU as the hardware accelerator. 

### Requirements 
- Keras 
- Numpy
- h5py
- Scipy + PIL + Scikit-image
  
### Instructions

Run on CPU with command:  
```
python generator.py [# of epochs]
```
