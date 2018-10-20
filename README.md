Runescape iron ore mining bot for the Dwarven Mines.

Written with python (cy2, numpy, pyautogui).

This code is for demonstration purposes only, to accompany an auto clicker creation guide found at [How to Write a Runescape Auto Clicker With Python](http://www.zaxrosenberg.com/how-to-write-a-runescape-auto-clicker-with-python-part-i/). Please use this program at your own risk.

Also, note that this code is resolution specific. Use the included find_cursor.py script to locate the proper pixels/ranges on your resolution and Runescape screen layout to adjust the IronBot.

Pre-requistes:

Now to install our packages:
Download the Numpy version corresponding to your Python installation from here. In my case, I’ve used numpy-1.12.1+mkl-cp36-cp36m-win32.whl. Type  pip install numpy-1.12.0+mkl-cp36-cp36m-win32.whl on the command line (PowerShell) to install.
Download the OpenCV version corresponding to your Python installation from here. In my case, I’ve used opencv_python-3.2.0-cp36-cp36m-win32.whl. Type  pip install opencv_python-3.2.0-cp36-cp36m-win32.whl on the command line (PowerShell) to install. This package is dependent on Numpy, and you will get an error if you haven’t installed Numpy first.
Install pyautogui by typing  pip install pyautogui on the command line (PowerShell). This module is the crux of our program, and what we’ll be using to control mouse movement/clicks and to “press” keys.
Optional: Download the pyHook or pynput for “listening” for keyboard or mouse inputs.

