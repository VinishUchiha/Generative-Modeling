## StackGAN - Text to Photo-Realistic Image Synthesis 

A **StackGAN** is named as such because it has two GANs that are stacked
together to form a network that is capable of generating high-resolution
images. It has two stages,
  * Stage-I
  * Stage-II
  
The Stage-I network generates low-resolution images with basic colors and rough sketches, conditioned on a
text embedding, while the Stage-II network takes the image generated by the
Stage-I network and generates a high-resolution image that is conditioned on
a text embedding. Basically, the second network corrects defects and adds
compelling details, yielding a more realistic high-resolution image. 
