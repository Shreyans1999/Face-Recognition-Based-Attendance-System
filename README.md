# FACE-RECOGNITION-BASED-ATTENDANCE-SYSTEM

## 1).ASTRACT
A Python GUI integrated attendance system using face recognition to take attendance.
In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

## 2).TECHNOLOGY USED:

i)tkinter for whole GUI
ii)OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
iii)Flask, CSV, Numpy, Pandas, datetime etc. for other purposes.


## 3).FEATURES:

i)Easy to use with interactive GUI support.
ii)Password protection for new person registration.
iii)Creates/Updates CSV file for details of students on registration.
iv)Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
v)Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

## 4).SCREENSHOTS

i)User will register its name and id by clicking on Add new user button.
![1](https://user-images.githubusercontent.com/38953782/232262142-d93127c7-61b2-4fa6-8c5a-ca87816a0d06.png)

ii)The moment you click on the button, the camera window will open for capturing the image of the user and get registered themselves into the database.
![2](https://user-images.githubusercontent.com/38953782/232262204-ae953754-3372-459c-ab13-a043a91a9471.png)

iii)Then click on the Take Attendance button to take the attendance as usual, for this camera will automatically detect the user's face and display their name on the screen.
![4](https://user-images.githubusercontent.com/38953782/232262455-91c5f6c8-d1bd-4cb0-9455-d1211a93031a.png)

iv)After then press ctrl+c to exit the camera window, then you would see that records have been automatically entered in the table with id and time.
![5](https://user-images.githubusercontent.com/38953782/232262557-b58cd542-89a9-4db3-ad0c-4bd0c453285c.png)

v)Finally, just go the Attendance folder and you will see that Excel sheet has maintained for storing the present records.
![6](https://user-images.githubusercontent.com/38953782/232262601-b4cfc301-68c4-4498-a072-78188216d56f.png)
