# Lung_Segmentation_Using_Adapted_UNet
This folder provides the source code for a two-stage framework based on adapted U-Net architecture to leverage automatic lung segmentation. 

Following are the steps of the this framework:

1. Extract CXR-patches (lung_patch_extraction.ipynb)

2. Train a modifed U-Net architecture to segment each individual cropped patches (train_main.ipynb)

3. Merge the segmented mask together to get an initial segmentation of lung feld (test.ipynb)

4. Post-process the initial segmentation to remove errors and noices (post_processing.ipynb)

The datasetting are demonstrated in the data_64 folder. Due to space capacity a sample dataset is uploaded here.

We used the Montgomery County X-ray Set, which is a public dataset. 

One can access the entire dataset from the following link:

https://academictorrents.com/details/ac786f74878a5775c81d490b23842fd4736bfe33
