# Brain MRI segmentation

This repo includes the results of the final project as a part of the annual retraining program called "Machine Learning for University Teachers" (HSE, 2021). 

The aim of the project was developing a neural network which will be able to detect 5 groups of brain structures, such as ventricles, amygdala, brainstem, hippocampus and gray matter. 

As a result of this work, several neural networks based on the 3D U-Net architecture were developed. 
Two of them with the highest results (DICE > 0.9) were selected:
● model with Crop transformation and Flip augmentation;
● model with Crop transformation and Flip, Anisotropy, Blur, Bias Field augmentations.

The developed models were applied on a dataset with pathological structures. Plots of volume distributions of the structures were built and analyzed.

## The thesis describing the results (in Russian): 
## The presentation (in Russian): 
