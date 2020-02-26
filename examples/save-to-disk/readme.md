# rs-save-to-disk Sample

## Overview

This sample demonstrates how to configure the camera for streaming in a textual environment and save depth and color data to PNG format. In addition, it touches on the subject of [per-frame metadata](../../doc/frame_metadata.md)

## Expected Output
The application should run for about a second and exit after saving PNG and CSV file to disk: 
![expected output](https://raw.githubusercontent.com/wiki/IntelRealSense/librealsense/res/save-to-disk-expected.PNG)

## Modified by- Raghav, Shivani
### save-to-disk sequence images:
As explained above what the original sample code rs-save-to-disk do we modified it in a way that before it only start for a second and gives output only single frame but now in the modified version the program not stops and runs continously till user wants and gives the output frames continously, user need to terminate the program to stop.
