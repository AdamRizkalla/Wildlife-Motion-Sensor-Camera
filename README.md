![Build Image](https://github.com/interactionresearchstudio/NaturewatchCameraServer/workflows/Build%20Image/badge.svg)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/interactionresearchstudio/NaturewatchCameraServer)
![GitHub all releases](https://img.shields.io/github/downloads/interactionresearchstudio/NaturewatchCameraServer/total)
# CameraServer

This is the main software for my wildlife camera. It is a Python server 
script that captures a video stream from a Pi Camera and serves it as a .mjpg 
through a control website to another device. The website can be used to start 
a photo capture or video capture based on motion detected in the frame. The 
software is designed to run on a Raspberry Pi Zero W.
## Configuring the wifi setup

The device automatically creates a hotspot network named MyNatureWatch-12345, with the numbers being a unique ID. 

## Access the interface

The website is then accessible through its IP address:

	http://192.168.50.1
	
If your device has Bonjour installed, you can also use:

	http://mynaturewatchcamera.local/