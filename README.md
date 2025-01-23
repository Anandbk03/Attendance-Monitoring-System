# Attendance-Monitoring-System
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for deatils of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.
6) You can send the attendance sheet through gmail.

STEPS:
1) Enter id and Name
2) click on Take Images.Wait untill the window closes.
3) Click on Save Profile and enter the password.(refer psd.txt).
4) Now data is stored and click on Take attendance.
5) press q to quit.
6) Attendance will be stored in excel sheet and the info will be displayed on the gui interface too.
7) In the code(main.py),fill your email and app password for enabling the functionality of sending the Attendance excel sheet via mail.
8) You can delete attendance,registrations or images taken as shown in screenshot.

# SCREENSHOTS
MAIN SCREEN:

![Alt text](https://github.com/Anandbk03/Anandbk03/blob/main/Screenshot%20(224).png)

CHANGE PASSWORD OPTION:
![Alt text](https://github.com/Anandbk03/Anandbk03/blob/main/Screenshot%20(225).png)
