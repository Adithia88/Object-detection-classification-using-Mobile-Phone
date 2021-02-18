# Object-detection-classification-using-Mobile-Phone

This is an implementation of object detecton + classification using Yolov4 Tiny and teachable machine on Python 3, then implement it to mobile phone.

![Object Detection Sample](assets/1.jpeg)

Download This: https://drive.google.com/file/d/18MGnFbQW8LV-eeSb_mCtkKqLUPaTUoZk/view?usp=sharing

The repository includes:
* Deploy it to Mobile phone 


# Getting Started
* Install Android Studio, u can download here https://developer.android.com/studio?hl=id
* Download this repo and download the android package (https://drive.google.com/file/d/18MGnFbQW8LV-eeSb_mCtkKqLUPaTUoZk/view?usp=sharing)
* deploy on mobile phone


# Change Object Detection Model yolov4

1. after u download this repo and android Package, go to that path using android Studio (exisiting project)

![extract data ](assets/1.png) 

2.open path app/assets , there u can see the model yolov4-416-fp-16.tflite 

![android studio ](assets/2.png)

3. Then click that model, press right mouse and show explorer, this will direct u too model path and coco.txt (label path)

![android studio ](assets/3.png)

4. Just change the model and coco.txt as yours, in this case we use (yolov4 tiny model u can see my repo, how to train it, and about coco.txt make as your labels)

![android studio ](assets/4.png)



# Change Classification Model 

1. just change model classifcation go to show explorer and change with your model

![android studio ](assets/8.png)


# Deploy On Android

1. go to build - build APK

![android studio ](assets/11.PNG)

2. from here u get the app just put it to gdrive and download it (app-debug.apk)

![android studio ](assets/12.PNG)



# result 

![android studio ](assets/1.PNG)
![android studio ](assets/2.PNG)
