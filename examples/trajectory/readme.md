
# rs-trajectory Sample
## Orignal
> In order to run this example, a device supporting pose stream (T265) is required.

## Overview
This sample demonstrates how to draw the trajectory of the device's movement based on pose data. 

## Expected Output
![expected output](https://raw.githubusercontent.com/wiki/dorodnic/librealsense/trajectory.gif)

The application should open a window split into 4 viewports: top (upper left viewport), front (lower left viewport), side (lower right viewport) and 3D (upper right viewport). In each viewport, a 3D model of the camera and the corresponding 2D trajectory are rendered.
In the 3D view, you should be able to interact with the camera using your mouse, for rotating, zooming and panning.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Modified by- Raghav, Shivani

### rs-trajectory-savetodisk_merge(matrix with images):
Here we need camera to run the program . In this code we merge the above modified code (1) bag to matrix by rs-trajectory and (2) save-to-disk sequence images together. By combining the above we are able to get the matrix text file and the frames for every matrix or we can say that by this code we get many frames according to camera movement and get the matrix for every frame which is stored or saved.
