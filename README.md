# kaggle-Steel-Defect-Detection
mxnet-gluon-based for  Steel Defect Detection with Kaggle-API, unet achieves 0.904+

## Network
- UNet: resnet50
    - Data augumentation: filp up-down, left-right, random-crop .etc
    - Filter small instances
- Loss: Normalized softmax Focal loss refer to [adaptis](https://github.com/saic-vul/adaptis)
- classification network: resnet50 + multi-classification

## Usage:

You can use kaggle api to train or inference on kaggle platform, you can refer to [kaggle-API](https://github.com/Kaggle/kaggle-api)



