# satellite-image-segmentation
This is sript for dataset on Kaggle https://www.kaggle.com/datasets/yaroslavnaychuk/satelliteimagesegmentation
# About Dataset

Source Images Description
The team of authors has constructed a new large-scale land-cover dataset with Gaofen-2 (GF-2) satellite images. This new dataset, which is named as Gaofen Image Dataset with 15 categories (GID-15), has superiorities over the existing land-cover dataset because of its large coverage, wide distribution, and high spatial resolution. The large-scale remote sensing semantic segmentation set contains 150 pixel-level annotated GF-2 images, which is labeled in 15 categories. Some of the images are from the paper: Land-Cover Classification with High-Resolution Remote Sensing Images Using Transferable Deep Models.
Source Link with Dataset

## Important
The resulting images are in .tif format and 256x256 resolution obtained with the patchify library. Masks contain values ​​from 0 to 15. Dataset use 50% of all source train images

## How I used this dataset?
I have tested various backbones with Unet architecture. MobileNet showed the best results. (0.44 IOU-score)

## Classes:
- background - 0
- industrial land - 1
- urban residential - 2
- rural residential - 3
- traffic land - 4
- paddy field - 5
- irrigated land - 6
- dry cropland - 7
- garden plot - 8
- arbor woodland - 9
- shrub land - 10
- natural grassland - 11
- artificial grassland - 12
- river - 13
- lake - 14
- pond - 15
