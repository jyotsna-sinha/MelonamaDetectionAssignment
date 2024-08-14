# Project Name
>Melanoma Detection  Model
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot 
of manual effort needed in diagnosis.

## Conclusions - 
* The class rebalance helped in reducing overfititng of the data and thus the loss is beng reduced but the acurracy is very low
* Accuracy on training data has increased by using Augmentor library
* Initially we tried without the ImageDataGenerator which created data to over fit at high ratio
* Then we introduced dropout and ImageDataGenerator which reduced the over fit
* At last we tried Batch Normalization and Augumentation which really helped in carry forward
* Model is still overfitting
* The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
* The Model can be further improved by tuning the hyperparameter



## Project Created by - Jyotsna Sinha
    

