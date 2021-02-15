# Face-Detection-Door-Unlock-Using-Python-and-Arduino

Libraries Required
  cv2 = pip install opencv-python
  pyserial = pip install pyserial
  time = pip install time
  pyttsx3 = pip install pyttsx3
  numpy = pip install numpy
  pillow = pip install pillow
  os = pip install os

How to run this project
1) Run '01_DataCollection.py' it will ask number put any desire. It will collect your face data and stores in dataSet folder. It will compute all data into the single yml file and    stores in recognizer folder.
2) Upload Arduino code.Use Arduino Ide (Note - keep haarcascade_frontalface_default.xml file in project folder don't delete.) 
2) Run '03_FaceRecognition.py' it will compare your live picture with stored data.
.............Done!
