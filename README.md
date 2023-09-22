# Optical-Mark-Recognition-Android

OMR Scanner android app made using OpenCV Android SDK capable of recognising simple omr sheet bubbles and generate the result using an answer key.

### Uses OpenCV contour detection and Image Processing to recognise darkened bubbles and prints the recognised answers with 95-100% accuracy.
### Takes an image of the OMR sheets and gives an option to crop it to make it fit the given discription and also to remove background noise.
### Saves it and then scans it using OpenCV and saves the results in a file which can then be checked with an answer key that was added prior to the scan.
### Can save an answer key and also modify existing ones within the app.


![Screenshot 2023-09-17 203820](https://github.com/NaimParvez/OmrScannerApp/assets/116740784/c7967682-bdea-490f-bf2e-961c9585fa5b)
![Screenshot 2023-09-17 203801](https://github.com/NaimParvez/OmrScannerApp/assets/116740784/1a720abe-88bb-4810-bb79-bc81634b43a4)
![Screenshot 2023-09-17 203649](https://github.com/NaimParvez/OmrScannerApp/assets/116740784/4f01fb9a-b004-4ef0-9864-f7e11d5e45ec)
<p> <img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/s1.jpeg" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/s3.jpeg" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/s2.jpeg" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/s4.jpeg" width =200 
  height = 350/>
</p>

### Can automatically check the answers with the defined answer key and grade individual scanned sheets.
### Can even scan an OMR directly from the computer screen in case of digital records with a good accuracy as well and provide similar results to a real OMR sheet.
### Can recognise upto 20 question blocks and more.
##
## Uses Otsu's Thresholding method to invert the foreground and background colors to detect filled bubble with ease and less effort.
<p> <img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/otsu_s_thresholding.jpg" width =200 
  height = 350/></p>
 
## This is an example on how it works
![Alt Text](https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/how_threshold_works.gif)

## See the app in action.
## Working of the app on 2 different OMR sheets taken stright from the computer screen.
## https://youtu.be/g2s8hGLgqaw
<p> <img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/sheet_1.jpg" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/KunalFarmah98/Optical-Mark-Recognition-Android/blob/main/app/src/main/res/raw/demo_1.jpeg" width =200 
  height = 350/></p>
