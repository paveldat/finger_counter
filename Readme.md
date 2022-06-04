# Finger Counter
In this project I am going to learn how to count fingers. 
I first look into hand tracking and then I will use the hand landmarks to count of the fingers.

## Features
* Can track your hand in real-time
* Can show the number of fingers raised

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/finger_counter.git`
2. Install all the requirements
`run libraries.bat` or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Hand Landmarks
<img src="https://github.com/paveldat/gesture_volume_control/blob/main/img/HandLandmarks.png">

## Result
<img src="https://github.com/paveldat/finger_counter/blob/main/img/result.gif">
