# mml2_image_matching

This project is to reconstruct 3D objects and buildings from images. For most of us, our best camera is part of the phone in our pocket. We may take a snap of a landmark, like the Trevi Fountain in Rome, and share it with friends. By itself, that photo is two-dimensional and only includes the perspective of our shooting location. Of course, a lot of people have taken photos of that fountain. Together, we may be able to create a more complete, three-dimensional view. What if machine learning could help better capture the richness of the world using the vast amounts of unstructured image collections freely available on the internet?

The process to reconstruct 3D objects and buildings from images is called Structure-from-Motion (SfM). Typically, these images are captured by skilled operators under controlled conditions, ensuring homogeneous, high-quality data. It is much more difficult to build 3D models from assorted images, given a wide variety of viewpoints, lighting and weather conditions, occlusions from people and vehicles, and even user-applied filters.

# Quick Navigation
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Repo Structure](#repo-structure)  
[Contact Info](#contact-info)  


# Background  

Typically, photos is 2D. It only includes the perspective of our shooting location. But how to create a more complete 3D view from a 2D photo is what we are looking for. In this project, we are going to leverage machine learning with the collection of free unstructured images available on the internet to help better capture the richness of the world.
The process to reconstruct 3D objects and buildings from images is called Structure-from-Motion (SfM). The key point of the problem is how to identify the pair co-visibility in two images by local features. By comparing local features, likely correspondences can be established between the pixel coordinates of image locations across  two or more images.
In this project, we are going to use machine learning to register two images from different viewpoints. The success of this project will make it possible to map the world using unstructured collections, and the results can also be applied to photography and cultural heritage preservation.

# Data

The dataset is provided by Kaggle: https://www.kaggle.com/competitions/image-matching-challenge-2022/data

# Models

LoFTR, SuperGlue, DKM

# Repo Directory Structure

The repository contains files for Image matching project, coding and other related materials.

Details:

- README.md: overall introduction and information of the project

- MML2_EDA.ipynb: Python coding notebook for exploratory data analysis on photos

- LoFTR: Folder for implementing LoFTR and DBSCAN

- MML2_Ensemble_Models.ipynb Python coding notebook for assembling models: LoFTR, SuperGlue, DKM and visualize the result.

- MML2_Presentation_Slides.pdf Slides for final presentation

Explanation:

The repo is structured as follows: All *0- (e.g., MML2-) files contain finalized work for the purpose described (e.g., "EDA"). 

# Contact Info

- Hongyu Dai hongyu.dai@vanderbilt.edu

- Zihan Fang zihan.fang@vanderbilt.edu

- Jingyuan Wu jingyuan.wu@vanderbilt.edu
