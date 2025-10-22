# Arm Dominance

# Table of contents
* [Introduction](#introduction)
* [Content](#content)
* [Instructions](#instructions)

# Introduction
This repository contains an example code on performing Statistical Shape Analysis on shape data.  The data we use in the script is different triangle shapes with their coordinates.

This script will demonstrate how Statistical Shape Analysis can be used on shape data by computing the shape coordinates into tangent coordinates, which allows us to implement other statistical methods, such as PCA and LDA, and analyze shape data.

# Content
The code covers the following steps:

1. Load(+ Installing) Packages 
2. Importing and Preparing Data
3. Plotting Data
4. Compute Tangent Coordinates
5. Perform Shape Principal Component Analysis(PCA)
6. Perform Linear Discriminant Analysis(LDA)
   
# Instructions
The code was tested on Mac operating systems, but should be compatible with Linux, or Windows systems. Recommended to use R version: R ≥ 4.0.0.

To run the code, make sure the script is run in the correct directory containing the data. 

For this triangle example, we used the Bookstein’s method of computing the Tangent Coordinates; however, we also included the code on how to compute the Tangent Coordinates using the Residual/procGPA method. To run those, uncomment the lines of code that uses the Residual/procGPA and comment the lines of code that use the Bookstein’s method. Then, you can run the script as is. 
