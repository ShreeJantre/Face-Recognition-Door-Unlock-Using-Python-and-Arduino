# Face-Detection-Door-Unlock-Using-Python-and-Arduino

Libraries Required
1) cv2 = pip install opencv-python
2) pyserial = pip install pyserial
3) time = pip install time
4) pyttsx3 = pip install pyttsx3
5) numpy = pip install numpy
6) pillow = pip install pillow
7) os = pip install os

How to run this project
1) Run '01_DataCollection.py' it will ask number put any desire. It will collect your face data and stores in dataSet folder. It will compute all data into the single yml file and    stores in recognizer folder.
2) Upload Arduino code.Use Arduino Ide (Note - keep haarcascade_frontalface_default.xml file in project folder don't delete.) 
2) Run '03_FaceRecognition.py' it will compare your live picture with stored data.
.............Done!
