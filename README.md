# Shutdown-App-Python-GUI

from tkinter import *: Imports all classes and functions from the Tkinter module.
import os: Imports the os module for interacting with the operating system.
Functions:
restart(): Restarts the computer immediately.
restart_time(): Restarts the computer with a 20-second time delay.
logout(): Logs out the current user.
shutdown(): Shuts down the computer immediately.
Tk(): Creates the main window for the application.
title("ShuDown App"): Sets the title of the window.
geometry("500x500"): Sets the initial size of the window.
config(bg="blue"): Sets the background color of the window.
Buttons:
Button: Creates buttons for Restart, Restart Time, Log-Out, and ShutDown.
place(): Specifies the position, height, and width of each button.
font(): Specifies the font style, size, and weight of the text on the buttons.
relief=RAISED: Sets the relief style of the buttons.
cursor="plus": Sets the cursor style when hovering over the buttons.
command: Specifies the function to be executed when the button is clicked.
