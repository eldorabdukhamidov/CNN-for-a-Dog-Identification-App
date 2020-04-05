## Deep Learning Nanodegree Foundation Project From Udacity

## CNN for a Dog Identification App

Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

## Libraries utilized

- **NumPy** - a fundamental package for scientific computing in python
- **Pandas** - an ease-to-use python library for manipulating data structures and performing data analysis
- **Jupyter Notebook** - tool that allow the creation of documents with live code
- **Matplotlib** - a plotting library for the Python programming language and its numerical mathematics extension NumPy.
- **CV2** - Computer vision and machine learning software library.
- **TQDM** - a progress bar library with good support for nested loops and Jupyter/IPython notebooks.
- **Torch** - an open source machine learning library
- **Torchvision** - a package consisting of popular datasets, model architectures, and common image transformations for computer vision.
- **PIL** - a free library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.

## Project Steps

- Import Datasets 
- Detect Humans
- Detect Dogs
- Create a CNN to Classify Dog Breeds (from Scratch)
- Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Write your Algorithm
- Test Your Algorithm

## Download Datasets
Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in this project's home directory, at the location ```/dog_images```.

Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the home directory, at location ```/lfw```.

## Instruction

1. Install [Anaconda](https://www.anaconda.com/distribution/).
2. Download the project
3. cd into the project folder
4. Run the code below to create and activate new environment

```
conda create --name bike_sharing_proj_env
```
 - Mac/Linux: 
```
source activate bike_sharing_proj_env 
```
 - Windows:
```
activate bike_sharing_proj_env
```
Install required libraries. For example, 
```
conda install numpy pandas matplotlib
```
```
jupyter notebook
```
