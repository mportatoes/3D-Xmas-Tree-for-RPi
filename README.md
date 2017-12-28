# 3D-Xmas-Tree-for-RPi

These instructions will enable you to set your PiHut 3D Xmas Tree to light up to music:

1) Install lightshowpi - http://lightshowpi.org/download-and-install/
2) Edit /home/pi/lightshowpi/config/defaults.cfg
  - Edit line 153 of the config file to include numbers 0-39
3) You can test to see if everything works by using:
  - sudo python /home/pi/lightshowpi/py/sychronized_lights.py --file=/home/pi/lightshowpi/music/sample/evilwezil_carol-of-the-bells.mp3
  
There are still some kits available as of the time of this edit: https://thepihut.com/products/3d-xmas-tree-for-raspberry-pi?variant=38284925265
