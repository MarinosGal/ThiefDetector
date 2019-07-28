# Description
A simple app that detects people, takes a photo of them and sends the photo via email.
It opens the web camera, detects a person and if found one, takes a photo and emails it to a prefered receiver.
The app supports only gmail smtp server and uses openCV library (https://opencv.org/).

# Run the application
1. install python 2.7
2. install openCV with command: <code>pip install opencv-python</code>
3. go to https://myaccount.google.com/lesssecureapps and change Allow less secure apps to ON
4. run the app to your directory as: <code>python thief_detector.py</code>
