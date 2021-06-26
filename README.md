# Labeled_ORAND-CAR-A
1024 training pics and 128 test pics in ORAND-CAR-A with single number labeled  

## Origin pictures
Origin pictures are from https://www.orand.cl/icfhr2014-hdsr/.  

>![图片](https://user-images.githubusercontent.com/54301366/123510499-8ccf9500-d6ae-11eb-9d5d-7c928cdc7a7d.png) ![图片](https://user-images.githubusercontent.com/54301366/123510503-92c57600-d6ae-11eb-89f1-8a2536ae465a.png)
>
>Two examples of CAR fields extracted from real bank checks.

## Label tool
Using https://app.roboflow.com/ to label all the images  
>![asd](https://user-images.githubusercontent.com/54301366/123511072-d077ce00-d6b1-11eb-8d6d-d818c5114190.gif)
> 
> How to use this website.

The dataset is saved in COCO format.  

## Final Results

>![a_car_000166_png rf 36b70a14806cfda4f8f9c5d4fb24da19](https://user-images.githubusercontent.com/54301366/123512359-885ca980-d6b9-11eb-84c2-448d098439ce.jpg)  
>7795

>![a_car_000154_png rf ec2ee980168b10a710ba6ae16c3f0b2c](https://user-images.githubusercontent.com/54301366/123512365-901c4e00-d6b9-11eb-819e-9c0b8967fcad.jpg)  
>2250


## File structure
```
ORAND-CAR-2014-coco  
├───annotations  
|   ├───instances_train2017.json  
|   └───instances_val2017.json  
|
└───images  
    ├───train2017  
    |   ├───a_car_000154_png.rf.ec2ee980168b10a710ba6ae16c3f0b2c.jpg
    |   ├───a_car_000155_png.rf.7d146a82570b6972a28dbdedde8d75a8.jpg
    |   └───...
    └───val2017  
        ├───a_car_007000_png.rf.2839d5138fa9e85635dea8b16eb3aeb5.jpg
        ├───a_car_007001_png.rf.61fb3b6020e6b39d98c516b3cb1eef23.jpg
        └───...    
```
