# Simple OPENCV Hand Tracker
Here's a simple implementation of a hand tracker made with Python, OpenCV, and Mediapipe.

![previewimage](https://github.com/vltmedia/SimpleOpenCVHandTracker/blob/master/images/quickHandTrackPReview.png?raw=true)

# Results:
Any hands in the scene will have a bone overlay showing each bone, and joint. User can then apply the rotation per join onto a robot, 3D object/character, or anything else.

# Requirements
- Anaconda
  - [Install Anaconda](https://docs.anaconda.com/anaconda/install/index.html)
- OpenCV
  - Open Anaconda Prompt
  - Create your OpenCV Environment ```conda create --name opencv-env python=3.5 ```
  - Install OpenCV to your new Environment ```conda install -c conda-forge opencv``` or [Install another OpenCV Version](https://anaconda.org/conda-forge/opencv)
- Media Pipe
  - Open Anaconda Prompt (in your applications/windows applications)
  - Activate the OpenCV Environment you made ```conda activate opencv-env```
  - Install MediaPipe ```pip install mediapipe```

# Usage
Open up Anaconda Prompt or any terminal using the Anaconda env you made.
- Activate the Conda ENV ```conda activate opencv-env```
- Run the Program ```python HandTracking.py```.
- Close the program with the ESC key.

# Video
[Tracking Results Video](https://www.dropbox.com/s/g0dez5hioaesgqw/QuickHandTracker%202021-07-17%2011-10-44.mp4?dl=0)
