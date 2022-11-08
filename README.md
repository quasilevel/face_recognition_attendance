# Face Recognition Attendance
**Note: Linux users were not recommended to use it as it requires to install an older version of Python which will clash with your current python version & there are a few more errors in the way.**

It is a Face Recognition based  Attendance System. It automatically matches the captured faces & marks their attendance without duplicity. It uses images as a database. You were required to set the individual's name as the image title in your database. Here DataBase is referred to `ImageAttendance` Folder.

## Requirements
- **Python 3.7 (only)**
- **Visual Studio (Desktop Development with C++)**
- **PyCharm**

## Installation
- Install [**Python 3.7**](https://www.python.org/downloads/release/python-379/) from here and set its path.
It should look something like this
![Python 3.7.9 ](https://github.com/KaroshiNara/face-recog-images/blob/main/Python-3.7.9.jpg)

- Install [**Visual Studio**](https://visualstudio.microsoft.com/downloads/) from here & use its Community Version as its free and will work perfectly too. After running its **.exe** select the **Desktop development with C++** option and hit Install
![Visual Studio](https://github.com/KaroshiNara/face-recog-images/blob/main/Visual%20Studio.png)

- Install [**Pycharm**](https://www.jetbrains.com/pycharm/) from here but don't set its path as Python 3.10

**Follow Steps to Run Code :-**

1. Open Pycharm
2. Select `Open` Option

![PyCharm-1](https://github.com/KaroshiNara/face-recog-images/blob/main/PyCharm-1.jpg)

3. Select the Folder `face_recognition_attendance-main` & click `OK`

![PyCharm-2](https://github.com/KaroshiNara/face-recog-images/blob/main/PyCharm-2.jpg)

4. Click on `File` then click on `Settings`

![PyCharm-3](https://github.com/KaroshiNara/face-recog-images/blob/main/PyCharm-3.jpg)

5. Select `Python Interpreter` in `Project:face_recognition_attendance-main` section, then check `Python Interpreter`  version should be set to `Python 3.7`, then click `+` button to install dependencies.

![Pycharm-4](https://github.com/KaroshiNara/face-recog-images/blob/main/PyCharm-4.jpg)

6. Now search for these dependencies and install them in this fixed order only :-
   - `cmake`
   - `dlib`
   - `face-recognition`
   - `numpy`
   - `opencv-python`
  
![Pycharm-5](https://github.com/KaroshiNara/face-recog-images/blob/main/PyCharm-5.jpg)


**Now you have installed all the requirements to run the project. Now all is left to run the `face_recognition_attendance.py`**

## Known Issues

Python 3.7 is compulsory to install beacuse there is a library  named `dlib` which is only working on Python 3.7 and needed for project.

