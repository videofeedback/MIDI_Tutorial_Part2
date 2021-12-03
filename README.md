# Midi_Tutorial_Part2
MIDI Blueprint for Camera Control

## This is the repository for the Midi Tutorial (Part 2) Blueprint.

V2 FIXES: 
- Added "Default Values" seaparated from the active Float Values so both settings never mix each other.
- Added Focus and Focal Length Default Values
- Added Channel 2 Sun Macros (Latitude, Azimuth, Intensity)

Note: If you want to collaborate with changes, please fork this repo and let us know about the changes. Thanks.


## Instructions
### 1) Create an Unreal Engine 4.27.1 "Virtual Production" project from templates.
### 2) Activate the MIDI plugin, and close Unreal Engine
### 3) Download the ZIP file of this Blueprint
### 4) Unzip the content of this file into the "Content" folder of your project.
### 5) Re-Start the project

## 6) Place the Blueprint "MIDI_CONNECT_V2" Inside the project.

[![](https://github.com/videofeedback/MIDI_Tutorial_Part2/blob/main/images/Map_Preview.png)]

### 7) Change the following settings in the red box

[![](https://github.com/videofeedback/MIDI_Tutorial_Part2/blob/main/images/midi_connectV2_Settings.png)]

## - Replace "Arturia BeatStep" with your MIDI Device ID
## - On "Camera", Select the camera to be controlled.
## - Sun: Sellect (BP_Sky_Sphere, SkyLight and Sunlight) from your blueprint. If the selections are blank, that means that you don't have those elements available on this map. Make sure that you open the "/VprodProject/Maps/Main Map). Otherwise place those elements to control the Sun.





