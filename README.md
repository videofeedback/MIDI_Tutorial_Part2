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
### 3) Download the ZIP file of this Blueprint [MIDI_CONNECT.ZIP](https://github.com/videofeedback/MIDI_Tutorial_Part2/files/)
### 4) Unzip the content of this file into the "Content" folder of your project.
### 5) Re-Start the project

## 6) Place the Blueprint "MIDI_CONNECT_V2" Inside the project.

[![](https://github.com/videofeedback/MIDI_Tutorial_Part2/blob/main/images/Map_Preview.png)]

### 7) Change the following settings in the red box

[![](https://github.com/videofeedback/MIDI_Tutorial_Part2/blob/main/images/midi_connectV2_Settings.png)]

## - Replace "Arturia BeatStep" with your MIDI Device ID
## - On "Camera", Select the camera to be controlled.
## - Sun: Sellect (BP_Sky_Sphere, SkyLight and Sunlight) from your blueprint. If the selections are blank, that means that you don't have those elements available on this map. Make sure that you open the "/VprodProject/Maps/Main Map). Otherwise place those elements to control the Sun.


# WANTED! CINEMA CAMERA FUNCTIONS!

If you want to colaborate with this project, there are few things that we need to fix (or find to be more exact).
This list
- Currect Aperture
- Exposure Component
- Camera ISO
- Camera Shutter Speed
- Color Grading (Temp)
- Draw Debug Focus Plane

All these featurea can't be located at level blueprint. (I can't)... I'll appreciate your colaboration. 
Note: Yes, I can find those on the "Detail" tab of the CinemaCameraActor, but I need to grab those elements from a BLueprint. 
If you have a working solution, please make a blueprint and copy "File.uasset" and send it to videofeedback@gmail.com (Subject "WANTED") and a brief explanation of how did you found those elements.
Only five different alternatives will be accepted, but everyone can submit your solution and all the solutions will be shared with the community.
You will be rewarded with 50 (VideoFeedback's NFTs (https://opensea.io/collection/ramiroslabfirstedition) ) *

Your name or any desire information will be published to the Open Source community (if desire). 
I appreciate your contribution.


[![Wanted](https://github.com/videofeedback/MIDI_Tutorial_Part2/blob/main/images/wanted_v1.png)


*The VideoFeedback NFT project is attached to multiple projects. It doesn't represents a monetary value, but can be traded in the open market. Do not assume that these NFTs can be traded at any price. This is still a project and there is no economic promisses other that the NFT community is willing to trade.

