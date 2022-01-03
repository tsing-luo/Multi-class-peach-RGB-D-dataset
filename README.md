# Multi-class-peach-RGB-D-dataset

# Introduction
  
The Multi-class-peach-RGB-D-dataset is composed by 2627 multi-modal images of 577 naked peaches and 2050 bagging peaches on tree filelds captured using Microsoft Azure Kinect camera. Each image contains 3 different modalities, including RGB image, Depth image and Infrared image. 

All images were aligned with the RGB image and manually labelled in 4 classes by occlusion status: non-occluded, occluded by leaves, occluded by branches and occluded by fruits. Find annotations in ".txt" format inside "annotations" folder. The following informations are some of the camera parameters.

### Color camera:
```
|Resolution|1280 x 720|
|FOV       |90° x 59° |
|Format    |   png    |
```
### Depth camera:
```
|Resolution|1024 x 1024|
|Mode      |    WFOV   |
|FoI       |120° x 120°|
```
### Folder structure:
```
Multi-class-peach-RGB-D-dataset
├── depth
│    ├── 1.png
│    └── ....
├── rgb
│    ├── 1.png
│    └── ....
├── infrared
│    ├── 1.png
│    └── ....
├── annotations
     ├── 1.txt
     └── ....       

```

>For more dataset, please contact Email:tsing999@stu.ahau.edu.cn, thanks.
