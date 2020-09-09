

# The drusen segmentation model for early AMD.

## Prerequisites
- Python 2.7 or Python 3.3+
- Pytorch 1.2.0
- sklearn
- albumentations
- cv2

## Testing
- Step 1: predict the segmentation mask with the trained DeepLab model. Please check the notebook file test_segmentation_Deep_lab.ipynb (Change all the PATH director before runing the notebook.)
- Step 2: predict the final drusen mask based on the results of step 1. Please check the notebook file test_main_model.ipynb (Change all the PATH director before runing the notebook.)

Note: the pre-trained models are provided in this [link](https://drive.google.com/drive/folders/1doM6ffbeI8zyI5ODh61MnZ08safQFWRp?usp=sharing).
## Training
- Step 1: train the DeepLab model. Please check the notebook file train_segmentation_Deep_lab.ipynb (Change all the PATH director before runing the notebook.)
- Step 2: predict the segmentation mask with the trained DeepLab model from step 1. Please check the notebook file test_segmentation_Deep_lab.ipynb (Change all the PATH director before runing the notebook.)
- Step 3: train the main model. Please check the notebook file train_main_model.ipynb (Change all the PATH director before runing the notebook.)

## Results
![alt text](https://github.com/QuangBK/drusen_seg/blob/master/fig_github.png?raw=true)
