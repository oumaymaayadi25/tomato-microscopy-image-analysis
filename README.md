# tomato-microscopy-image-analysis
Image analysis and automated segmentation of tomato fruit microscopy images using Fiji/ImageJ and Cellpose-SAM.

## 1. Overview

This project was conducted as part of my final-year engineering project at INRAE PACA, Avignon, France

The project investigated the effects of genetic variability and fruit developmental stage on chloroplast abundance, chlorophyll production and carotenoid biosynthesis in tomato (Solanum lycopersicum).


## 2. Context & Problematic

### Context

Chloroplasts are abundant during early tomato fruit development. They contain chlorophyll and support photosynthesis, while their abundance, size, and spatial distribution may influence photosynthetic activity and carotenoid accumulation during fruit development.

### Problematic

Although carotenoids are important for tomato fruit quality and nutritional value, the relationship between **chloroplast structural traits** and
**carotenoid accumulation during fruit ripening** remains incompletely characterized.

A major challenge is therefore to **accurately quantify chloroplast features in situ** and investigate how these cellular traits vary across genetically diverse tomato varieties and developmental stages.

## 3. Research question

Although carotenoids are important for tomato fruit quality and nutritional value, the relationship between chloroplast structural traits and carotenoid accumulation during fruit ripening remains incompletely characterized.

A major challenge is therefore to accurately quantify chloroplast features in situ and investigate how these cellular traits vary across genetically diverse tomato varieties and developmental stages.

How do chloroplast abundance, size, and spatial distribution vary across tomato genotypes and fruit developmental stages, and how are these traits related to carotenoid accumulation?

## 4. Workflow

Tomato varieties (4)
↓
Fruit developmental stages
↓
Biological sampling
↓
Confocal microscopy
↓
Image processing
↓
Image segmentation
↓
Quantitative image analysis
↓
Biochemical measurements
↓
Data interpretation

## 5.  Cellpose-SAM

Cellpose-SAM was used to perform automated segmentation of chloroplasts from microscopy images.

The model identifies individual objects in the image and generates segmentation masks that can subsequently be analyzed quantitatively.

## 💻 Code

The image segmentation workflow was implemented in Python using Google Colab.

👉 [Open the Google Colab notebook]: [https://colab.research.google.com/drive/1ZdkMSUMCL4flSlvxHc1M6uioEyRkMJ41?usp=sharing]
or 
*** see Cellpose-sam-seg.ipynb file ***

