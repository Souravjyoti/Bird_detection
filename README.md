# Bird_detection
A possible solution to avoid airplane nightmare.

Directions:

  1) Clone the project to your PC.
  2) Run the Bird_detection.py file on your terminal.
     You can use web-cam for real-time detection just by changing the video name in the python file with 0 (0 is the default web-cam number if you are connected to only one).

Introduction:
  
  Many airplane disasters till date have taken place because of birds. Birds flying near the runways are a constant threat
to planes. Therefore this project aims at detecting birds in and around the airports and also produce a warning(this part is yet to be added). 

Description and working:

  This model works both on preloaded video as well as on web-cam in real time. This project is based on haar-cascade and therefore the central focus is to build thecascade file(xml file). I have downloaded background pictures from Image_Net and trained them using three positive bird pictures. Because my CPU is not that powerful, I could not train it more, and hence the accuracy is a bit low.
  
  Here are some snaps of the program......
  
 ![screenshot1](https://user-images.githubusercontent.com/31644207/43323516-7f56488c-91cf-11e8-8649-55983896b71b.jpg)
  
  With larger data and more computation power, this model can be improved to a great extent.
  
