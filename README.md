# Classification of blinding retinal diseases
## Classification of blinding retinal diseases using Residual Learning and Convolutional Layers

- To download image data and checkpoints: https://drive.google.com/open?id=1aDKW6FIKmy6q_EcvuqvnhTryX8K0fK6a
- Credit Image Set: https://www.kaggle.com/paultimothymooney/kermany2018/data#
- "Tools" for my project: Tensorflow 2, Python 


In this project I compared three neural networks for classifying retinal diseases. The data consists of more than 32 thousand optical coherence tomography (OCT) images of the retina separated equally in four classes across train/val/test datasets.

The project is written in Jupyter Notebook. The whole process is exlained from the image processing to the training and testing of the models. Further work:
- test other image processing methods;
- achieve lower training error on the best architecture;
- improve explainability of the model by showing feature maps and possibly implementing Grad-CAM.

### Neural Networks Architecture

![](models_blocks.jpg) 
