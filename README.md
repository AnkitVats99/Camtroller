# Camtroller

## Short Intro
Playing games like Hill Climb Racing using OpenCV (NO Keyboard required) with Hand Gestures.

## How to use it?

* Clone the repository </br>
* Start the game (Racing Game)</br>
* Execute gesturecontrol.py file</br>

## Controls :-

* Right Hand Fist- Acceleration
* Left Hand Fist- Break

## Requirements :-

* python 3.x
* imutils
* numpy
* opencv-python

## Description :- 

Using OpenCV, the screen is divided in such a way that the bottom left region of the screeen is used for applying breaks, whereas bottom right region of the screen is used for acceleration. </br></br>

When a navy blue circle(fists in navy blue gloves) is detected in any of the regions, corresponding key is given as input to the game from our program.</br>
</br>
NOTE: No machine learning model is used for detecting objects!!

## Credits :-

* [OpenCV](https://opencv.org/) </br>
* [Hill Climb Racing](https://hillclimb-racing.com/)  </br>
* [directkeys.py](https://stackoverflow.com/questions/14489013/simulate-python-keypresses-for-controlling-a-game)  </br>



