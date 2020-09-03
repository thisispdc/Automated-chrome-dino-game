# Automated-chrome-dino-game
This is an automated chrome dino game which works based on pixel detection of the cactus and bird and uses pyautogui to perform keyboard inputs.
In order to run this code, you would need to have python interpretor ready, 
go ahead and install following by typing the commands below
1. PyAutoGui: pip install pyautogui
2. Pillow: pip install pillow.

This program primarily works on the principal of image processing. It initially captures the the screenshot and converts the image into greyscale. A rectangle is drawn for the cactus and the bird each taking the co-ordinates. This is what going to take alot of time as it is hit and trial approach to position the rectangle. It then detects the pixel value of obstacles such as cactus or birds (0-255). If pixel of higher value such as black appeares in the drawn rectangle, It performs the required keyboard action.

Once you have installed all the modules, just navigate to the project location in your terminal and run the command "python <fileName.py" and get ready to trick your friends!
