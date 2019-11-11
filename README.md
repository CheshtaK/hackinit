# Hackinit
Secured the runners up position for creating a project to help navigate visually impaired people

## Idea

With this, we aim to help visually impaired people become independent. It can detect obstacles in the person’s way and hence guide them accordingly. 
We use audio cues to guide the person to the correct or obstacle free path. In further development we intend to use a physical device that would correct the path in certain circumstances. The project incorporates computer vision, machine learning and an IP camera for software implementation. Whereas for hardware the project uses adrino, ATMEGA-162, Ultrasound sensor. With the sensors, it combines the data from software with hardware to get more accurate results. Moreover this device is put on a 'Walkinng Stick', and wirelessly connected to a mobile device for processing. Audio cues and rotator is used to provide direction results.


## Implementation

We detect the obstacle and after detecting the object, navigation path are given to the user. For being economical we use a camera feature instead of relying on acquired help like guide dogs. We’ve used the Single Shot Detector (SSD) which provides a good balance between speed and accuracy since the project would work on real-time implementation. The COCO dataset is used for the objects. The code is written in python and tensorflow is used as machine learning backend. An IP camera is used to get live feed and process the result. This result is further compared and fed to a python file that takes in sensor data and processes the data. This result is then compared to threshold values and audio cues are provided.

![alt-text](https://github.com/AkhilDixit1998/Raah-Darshni/blob/master/outputs/finaloutput.gif)
