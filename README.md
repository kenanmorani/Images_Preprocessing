# Images_Preprocessing
## 1. segmentation and cropping.py code 
The code uses python open-cv for gussian blurring, cropping and histogram segmentation of medical images. The code is an attempt to segment lung CT scan images. 

The original Image looks like:
<p align="center">
  <img src="https://github.com/kenanmorani/Images_Preprocessing/blob/main/FIgures/original.png" /> <br/>
  Taken from COV19-CT-DB Database 
</p>      
<br/>

The resulting image looks as follows:
<p align="center">
  <img src="https://github.com/kenanmorani/Images_Preprocessing/blob/main/FIgures/cropped%20and%20segmented.png" />
</p>      
<br/>

## 2. COV19D_CT_images_Processing_Using_Contour_Cropping.ipynb
In an attempt to segment and highlight region of interests in the images, this code applies a function to crop Region of Interests on the CT images using open-cv. Results of cropping can be seen in the code on one of the CT images- a central slice.

## 3. Image-Segmentation-Methods-Comparison.ipynb
The notebook compares three different segmentation methodds; thresholding [otsu], Edge-Based, and Region-based.
