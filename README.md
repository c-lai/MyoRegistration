# MyoRegistration
**ImageRegistration.m** is the script for registering tif images to dicom images.  
**RegAlgorithm.m** is the registration function.  
**transform_image.py** is the script for applying transformation matrixes.  
  
## Registration Algorithm
Images are enhanced in the first step, which includes normalization, histogram equilibrium and anisotropic diffusion. Then images features are extracted using blob detection (SURF). At last, match corresponding features in 2 images and compute the transformation matrix.  
  
## Test
Run **ImageRegistration.m** and **transform_image.py** at the folder of dataset (keep the directory the same as USB disk).
