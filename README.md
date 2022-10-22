## Fast re-OBJ: Real-time object re-identification in rigid scenes 
by Ertugrul Bayraktar, Yiming Wang, and Alessio Del Bue

The repository for the paper **Fast re-OBJ: Real-time object re-identification in rigid scenes** published at Machine Vision and Applications.

You can access the dataset through the link located at: **https://tinyurl.com/bdsb53c4**

This folder contains the dataset explained in the paper. The paper is published at Machine Vision and Applications.

Detailed Expalanation for the Dataset:
*	All of the folders, namely background (bg), foreground (fg), and full_images, contain the same subfolders of scenes. 
*	The bg images are obtained by extracting the object of interest from the entire image, namely full image, and replacing the values of pixels corresponding to the object of interest by zeros that makes that region completely black.
*	The fg images are obtained by extracting the bg images from the full images, or vice-versa.
*	The numbers in the scene000XYZ_0N subfolders stand for the IDs of individual objects.
*	The numbers; 1, 2, and 3 in the ID subfolders denote the Anchors (A), Positives (P), and Negatives (N), respectively. 
*	Each of A, P, and N contains 8 images with .jpg format.
*	All of the images have the dimension of 1296x968.

- scenes2dgt folder also contains the same scene subfolders with bg, fg, and full_images folders, which further includes the frame number, ID, class label, and bounding-box locations as the ground-truth for each ID.
- The code repository for generating the results are located at: **https://github.com/bayraktare/fast_re_OBJ** *(this page)*

## Citing Fast re-OBJ:
If you find this dataset or paper itself useful in your research, please consider citing as follows:

*@article{bayraktar2022fast, \
title={Fast re-OBJ: real-time object re-identification in rigid scenes}, \
author={Bayraktar, Ertugrul and Wang, Yiming and DelBue, Alessio}, \
journal={Machine Vision and Applications}, \
volume={33}, \
number={6}, \
pages={1--12}, \
year={2022}, \
publisher={Springer} \
}*

