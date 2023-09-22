# Optical-Mark-Recognition-Android

OMR Scanner android app made using OpenCV Android SDK capable of recognising simple omr sheet bubbles and generate the result using an answer key.

### Uses OpenCV contour detection and Image Processing to recognise darkened bubbles and prints the recognised answers with 95-100% accuracy.
### Takes an image of the OMR sheets and gives an option to crop it to make it fit the given discription and also to remove background noise.
### Saves it and then scans it using OpenCV and saves the results in a file which can then be checked with an answer key that was added prior to the scan.
### Can save an answer key and also modify existing ones within the app.



<p> <img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/c7967682-bdea-490f-bf2e-961c9585fa5b" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/1a720abe-88bb-4810-bb79-bc81634b43a4" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/4f01fb9a-b004-4ef0-9864-f7e11d5e45ec" width =200 
  height = 350/>
<img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/446fe286-1358-4541-959a-7825c8d72379" width =200 
  height = 350/>
</p>

### Can automatically check the answers with the defined answer key and grade individual scanned sheets.
### Can even scan an OMR directly from the computer screen in case of digital records with a good accuracy as well and provide similar results to a real OMR sheet.
### Can recognise upto 20 question blocks and more.
##
## Uses Otsu's Thresholding method to invert the foreground and background colors to detect filled bubble with ease and less effort.
<p> <img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/1f1a834b-5a5e-42d4-b326-387422f2e0e8
" width =200 
  height = 350/></p>
 
## This is an example on how it works
![Alt Text](https://github.com/NaimParvez/OmrScannerApp/assets/116740784/e2efd093-1582-42ef-a307-d666bd527120)

## Here is a test answer sheet.
<p> <img hspace="10" src="https://github.com/NaimParvez/OmrScannerApp/assets/116740784/387c9ba5-4e84-433c-8ccb-2f62dfd6ebe8" width =200 
  height = 350/></p>

