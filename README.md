# ResNet-18-Caffemodel-on-ImageNet
## Accuracy
We reported the test accuracy on **ImageNet (ILSVRC2012 Validation Set)**.    

DataSet | Top-1 | Top-5 | Loss
------------ | ------------- | ------------- | -------------
Both256 | 67.574% | 88.1001% | 1.33896
Shrt256 | **69.0801%** | **89.0321%** | **1.2711**

## About shrt 256
Augmented training and test sample:  
> This improvement was first described by Andrew Howard [Andrew 2014]. Instead of resizing and cropping the image to 256x256, the image is proportionally resized to 256xN(Nx256) with the short edge to 256. Subcrops of 224x224 are then randomly extracted for training. 

## Model Link
[OneDrive](https://1drv.ms/u/s!Av1MQK8mV3J8btF8hWlK9D8LGrk)<br>
[BaiduCloud](http://pan.baidu.com/s/1jI5LeQy)


