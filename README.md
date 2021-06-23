# gaze-controlled-keyboard-with-automated-suggestion
# Gaze-controlled-typing

The motive of this project is to implement the technology for a better tomorrow. This project allows users to control the keyboard through eye movement. Not only this you can even use it as a mouse for some of the basic operations like minimizing or maximizing the tab or choosing a file etc. Later the automated completion of text written with eye movement will be included for the ease of writing. This is an initiative taken for the betterment of disabled people.

**Code Requirements**

1. Numpy 
2. OpenCV
3. PyAutoGUI
4. Dlib
5. Imutils 
 
 **Core Logic**
 This project is mainly an amalgam of OpenCv, Pyautogui and NLP.
 All the detection part is mainly done with the help of OpenCv library of python. We are taking the frames in real time from the webcam, so to detect the eyes we will use face landmarks detection approach. We can find 68 specific landmarks of the face.
 
 
 
 ![land](https://user-images.githubusercontent.com/77487483/123156460-f1a8a680-d486-11eb-8640-40db6058670d.png)



To get a better understanding of how do we get frames in real time and the detection of eye and blinking is separately being shown in Eye_Detection and Eye_Blinking_Detection.
 

 **Execution Order**
 1. Follow these installation guides - [Numpy](https://pypi.org/project/numpy/), [OpenCV](https://anaconda.org/conda-forge/opencv), [PyAutoGUI](https://anaconda.org/conda-forge/pyautogui), [Dlib](https://anaconda.org/conda-forge/dlib), [Imutils](https://anaconda.org/conda-forge/imutils).
 2. Download the models given above in model. txt
 
 **Usage**
 1. Opening of mouth is taken as the activation of cursor.
 2. Left wink is equivalent to the left click .
 3. Right wink is equivalent to the right click.
 4. Head movements are related with the movement of cursor. To move the cursor to right side, move your head to the right and vice versa.
 5. To de-activate the mode squint your eyes. 


