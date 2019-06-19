# Vision Framework
An adaptive framework detailing the methodology to properly detect, filter, and calculate information based off of objects using OpenCV. 

Features include
* GPU Acceleration
* Multi-Camera Support
* Filtering by multiple parameters (Area, Aspect Ratio, Solidity Ratio, etc)
* Displaying contours and thresholds
* Live tuning of thresholding values
* Networking using ZMQ or NetworkTables

## Instructions
1. Clone the repository
2. Edit VisionFramework.cpp to your needs as directed by the comments or add in your own features.
3. Once the .cpp file is complete, create a build sub directory.
4. Compile the program using ``` cmake.. ```. This uses the CMakeLists.txt located directly above the build folder to create a Makefile.
5. Run ``` make ``` to build the Makefile into an executable, which you can then run with ``` ./VisionFramework.cpp ```
