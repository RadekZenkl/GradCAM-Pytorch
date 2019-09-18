### A Pytorch implementation of GradCAM[1], GradCAM++[2], and Smooth-GradCAM++ [3]
<br>
<p align="center">
<img src=assets/readme.png>
</p>

### Supported torchvision models
- alexnet
- vgg
- resnet
- densenet
- squeezenet

### Usage
please refer to `example.ipynb` for general usage and refer to documentations of each layer-finding functions in `utils.py` if you want to know how to set `target_layer_name` properly.

### References:
[1] Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization, Selvaraju et al, ICCV, 2017 <br>
[2] Grad-CAM++: Generalized Gradient-based Visual Explanations for Deep Convolutional Networks, Chattopadhyay et al, WACV, 2018
[3] Smooth Grad-CAM++: An Enhanced Inference Level Visualization Technique for Deep Convolutional Neural Network Models, Omeiza et al, 2019
