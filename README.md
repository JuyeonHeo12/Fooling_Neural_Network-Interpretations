# Fooling Neural Network Interpretations via Adversarial Model Manipulation

## Abstract
We ask whether the neural network interpretation methods can be fooled via adversarial model manipulation, which is defined as a model fine-tuning step that aims to radically alter the explanations without hurting the accuracy of the original models, e.g., VGG19, ResNet50, and DenseNet121. By incorporating the interpretation results directly in the penalty term of the objective function for fine-tuning, we show that the state-of-the-art saliency map based interpreters, e.g., LRP, Grad-CAM, and SimpleGrad, can be easily fooled with our model manipulation. We propose two types of fooling, Passive and Active, and demonstrate such foolings generalize well to the entire validation set as well as transfer to other interpretation methods. Our results are validated by both visually showing the fooled explanations and reporting quantitative metrics that measure the deviations from the original explanations.  We claim that the stability of neural network interpretation method with respect to our adversarial model manipulation is an important criterion to check for developing robust and reliable neural network interpretation method. 

## Materials

1. [Paper](https://arxiv.org/abs/1902.02041)
1. [PPT](Materials/PPT.pdf)
1. [3-min Video](Materials/Video.md)
1. [Poster](Materials/Poster.pdf)

## Methods

## Experimental Results

## How to run our codes
