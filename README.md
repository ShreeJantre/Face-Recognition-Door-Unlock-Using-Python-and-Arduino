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
1) Run '01_DataCollection.py' it will ask number put any desire. It will collect your face data and stores in dataSet folder.
2) No need to run '02_Trainer.py' this file run automatically once you run first file & It will compute all data into the single yml file and stores in recognizer folder. (Note -     keep haarcascade_frontalface_default.xml file in project folder don't delete.)
3) Upload Arduino code.Use Arduino Ide  
4) Setup Arduino and Servo Motor. If you don't know how to setup I have added circuit diagram of Arduino and Servo Motor this will help you to setup hardware. 
5) Run '03_FaceRecognition.py' it will compare your live picture with stored data. If face matches then Door will open for 5 seconds and after it will get closed.
.............Done!
