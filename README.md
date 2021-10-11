# OCT-Angio

1.	Introduction
This project comes under image processing to get OCTA processed images and layers.

2.	Inputs and Outputs
File Name: Python_OCT_A.py
Input: OCT cube tiff images
Output: CSV files based on no. of inputs

3.	Requirements
Version 3.8 and above is good to run this project. CPU needs to support multiprocessing techniques and needs some python packages. Multiprocessing techniques is used to optimizing time.

You can run this .PY file only in terminal like following example command.

Example: python .\ Python_OCT_A.py C:\Users\ACER\Desktop\BM-OCTReconstructedImage C:\Users\ACER\Desktop\BM-OCTReconstructedImage\Output
 
Input folder: C:\Users\ACER\Desktop\BM-OCTReconstructedImage has 384 reconstructed tiff images from raw data.
 
Output folder: C:\Users\ACER\Desktop\BM-OCTReconstructedImage\Output. It will create three folders in output path to store variance images, composite images and 128 CSV files each file has 8 layers based on your image size.

4.	Conclusions
We made a project with maximum accuracy and also accuracy changes based on image quality. If you still need more accuracy in segmented layers, to get adjust via axial resolution, lateral resolution and smoothing (savgol filter) values. If you still need more accurate composite images, to get adjust via alpha and beta values.
