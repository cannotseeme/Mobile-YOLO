# Mobile-YOLO
## A mobile helmet detection method. The method is mainly based on the MobileNetv2 and YOLOv4
### The project utilizes the Darknet from https://github.com/AlexeyAB/darknet
### Dir cfg contains the configuration files
### Dir weights contains the weight files
### Dir mobile contains configuration and weight file after weight quantization using NCNN https://github.com/Tencent/ncnn

## Results
The model is trained on VOC2007+2012 train&val and tested on VOC2007 test dataset with an mAP of 73.1.
Results on private helmet dataset is 89.3%.

## TO begin
### PCs
Please follow https://github.com/AlexeyAB/darknet to setup. Replace the .cfg and .weights files with our files.
### Mobile Devices
Please follow https://github.com/Tencent/ncnn to setup and use our .param and .bin files.
