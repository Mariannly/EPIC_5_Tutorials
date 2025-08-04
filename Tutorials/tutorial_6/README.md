# Tutorial 6: AI for bioimage analyisis (Andrés Morales-Navarrete, UDLA)

This class is an introduction to image analysis of biological images (i.e. microscopy images) using classic and deep learning methods.

We will use python 3.x (as python2 is not supported anymore). Similarly, we will mainly use jupyter notebooks (.ipynb) for the courses taught at this course.

- Jupyter notebooks are very useful tools for learning programming because they provide a nice visual and interactive interface.
- You can see the results of your code live, instead of waiting till your script (.py) finishes running in a terminal.


To be able to use python and jupyter notebooks in your laptop, there are several options:

#### OPTION 1: Google Colab (see https://colab.research.google.com/):

**Important Note: We highly recommend this option for participants with little programming experience.**

One option is to use Google Colab, for which you would need a Google account, which can be a personal gmail account or an institutional email account supported by Google. The advantage of using Google Colab is that all libraries are installed in a Linux server remotely, so we don't need to worry about compatibility issues, different operating systems, etc. The disadvantage is that Colab provides limited memory and computing resources as everything runs in a cloud, so you can only use it to process small datasets.


1. Log into your Google account.

2. Upload the notebooks and the image data (tiffs and jpgs)


	
#### OPTION 2: Anaconda/Miniconda:
	- Create environment:
	$ conda create -n py38 python=3.8 anaconda -y
	- Activate the environment:
 	$ conda activate py38	
 	- Install a few extra libraries:
 	$ conda install scipy scikit-image tifffile
 	- Open a jupyter notebook
 	$ jupyter notebook


### 1. Introduction to Digital Images
- Brief intro to digital images

	* [0_Intro_DigitalImages.ipynb](./code/0_Intro_DigitalImages.ipynb)
	* GoogleColab:
 		[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ciencialatitud0/EPIC_5/blob/main/Tutorials/tutorial_6/code/0_Intro_DigitalImages.ipynb)
 
 
### 2. BioImage Analysis with Python

- It is a step by step pipeline for segmenting cells in 2D fluorescence microscopy images (with labeled membranes)
	* [1_Image_analysis_tutorial.ipynb](./code/1_Image_analysis_tutorial.ipynb)
	* GoogleColab:
	[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ciencialatitud0/EPIC_5/blob/main/Tutorials/tutorial_6/code/1_Image_analysis_tutorial.ipynb)


### 3. Noise Removal using Autoencoders
- Short description
	* [2_NoiseRemoval_Autoencoders.ipynb](./code/2_NoiseRemoval_Autoencoders.ipynb)
	* GoogleColab:
	[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ciencialatitud0/EPIC_5/blob/main/Tutorials/tutorial_6/code/2_NoiseRemoval_Autoencoders.ipynb)

### 4. Image Segmentation using UNet
- Short description
	* [3_ImageSegmentation_UNet.ipynb](./code/3_ImageSegmentation_UNet.ipynb)
	* GoogleColab:
	[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ciencialatitud0/EPIC_5/blob/main/Tutorials/tutorial_6/code/3_ImageSegmentation_UNet.ipynb)

## Disclaimer
- Part of these materials have been adapted from the original versions: 
    - "Python BioImage Analysis Tutorial:" https://github.com/WhoIsJack/python-bioimage-analysis-tutorial
    - "Python Workshop - Image Processing" : https://github.com/karinsasaki/python-workshop-image-processing
