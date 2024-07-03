# Handwritten Digit Calculator using Knowledge Distillation (KD)
A deep learning project using Knowledge Distillation on a convolutional neural network (CNN) that can recognise handwritten mathematical symbols. The model has been integrated as a calculator able to calculate the value of handwritten mathematical expressions. 

This project has been developed using the [Basic Handwritten Math Symbols Dataset](https://github.com/wblachowski/bhmsds?fbclid=IwAR2WbJRLMxecP4a41iTjJR-_idug6anFvjFdz8XyinaZV7gA8OFwaah7MR8) and is the final project of the Deep Learning course at Aarhus University. 


## Contents
- Two ipynb files: One containing the CNN model without KD (project.ipynb) and one implementing the KD network (project_optimized.ipynb) 
- Test images for evaluating the calculator 
- Pretrained models of the teacher, student and KD student 

## Prerequisites
- Python 3.7 or higher
- Jupyter Notebook 

Furthermore, the following packages and libraries are used in the project
- Pandas
- Numpy
- PyTorch
- Sympy
- Imutils
- Matplotlib

## Usage
1. If you want to train new models, run the project_optimized.ipynb from the start.
2. If you want to evaluate the pretrained models (or newly trained models), run the cells from the "Testing" section. 


## Authors and Contributions
Bastian Aron Kramer<br/>
Email: 201908709@post.au.dk<br/>
StudyID: 201908709

Emil Chao Hu<br/>
Email: 201907692@post.au.dk<br/>
StudyID: 201907692

Magnus Trøjgård Tang<br/>
Email: 201904915@post.au.dk<br/>
StudyID: 201904915
