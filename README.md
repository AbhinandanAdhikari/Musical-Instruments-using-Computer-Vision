# Virtual Musical Instruments :drum: :musical_keyboard: :notes:

- It helps users to virtually play musical instruments by waving their __hands while holding a coloured object__ in the air.
- It detects the __coordinate position__ of the hand using __colour detection__ and, depending on it, presses the keyboard button and plays the respective instrument sound.
- This project uses the concept of __Computer Vision__ and is implemented using ```Python```, ```OpenCV```, ```Numpy```, ```PyAutoGUI```.

# System Requirements:

- ```Python```
- ```OpenCV```
- ```PyAutoGUI```
- ```Numpy```
- ```Web Camera```

# How to use:
## For Drumkit set :drum:
- Hold any blue/red colored object in your hand.
- Open [OneMotion](https://www.onemotion.com/drum-machine/) in your browser.
- Run your python file.
- Keep both OneMotion & your output window side by side. 
- Just wave your hand holding that object infront of camera and move towards any insturment.
- It will press the keyboard button depending on the instrument and will play the sound.

## For Piano :musical_keyboard:
- Wear black colored gloves.
- Open [ONLINE PIANIST](https://www.onlinepianist.com/virtual-piano) in your browser.
- Run your python file.
- Keep both Online Pianist window and your output window side by side.
- Just wave your hands/fingers while wearing black gloves in front of the camera.
- It will press the keyboard button depending on the keys of the piano and will play the sound.
# Concepts used:

- __Color Tracking__ : It tracks the colored object held at hand.
- __Contour Detection__: Detects the position of the colored object and making a rectangle over it.
- __Image Masking__: Image mask is created after detecting the color.
- __Color Space Conversion__: Converts the BGR into HSV values.
