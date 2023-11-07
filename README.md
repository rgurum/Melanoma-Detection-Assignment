# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Dataset of images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)
- Background of this project: The goal is to find a pattern for the disease with the images.

## Conclusions
- seborrheic keratosis class has the least no of sampels
- (melanoma, pigmented benign keratosis) and (actinic keratosis, dermatofibroma) have the proportionate no of samples
- pigmented benign keratosis has more samples among others where melanoma is second one.
- Final model trained with augmented data - has the best accuracy score where it correctly find the melanoma disease that can be seen in the end of ipynb file.

## Technologies Used
- tensorflow - 2.14.0
- seaborn - 0.12.2
- numpy - 1.25.2
- keras - 2.14.0
- pandas - 2.0.3
- matplotlib - 3.7.2
- Augmentor - 0.2.12

## Contact
Created by [@rgurum] - feel free to contact me!