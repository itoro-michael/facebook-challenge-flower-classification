# Facebook PyTorch Challenge

Facebook's support and investment made 10,000 seats available for a new Udacity Challenge Course titled, 
Introduction to Deep Learning with PyTorch. This repository contains the 102 flower category classification model created as part of the Challenge.


## 102 Flower Category Classification

The classification model is built using transfer learning on the 201 layer DenseNet pretrained model from torchvision. The classifier layer of 
the pretrained model was substituted with a fully connected classifier layer with 102 outputs. Only the weights of the replaced final 
classifier layer were trained in the project.

The dataset for the project is derived from the 102 Flower Category Database of the University of Oxford.

The model has achieved 97.4% accuracy on validation set.