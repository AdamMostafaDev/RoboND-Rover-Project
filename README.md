# Search and Sample Return Project

This project is modeled after the NASA sample return challenge and it tackles the three essential elements of robotics, which are perception, decision making and actuation. This project is carried out in a simulator environment built with the Unity game engine.

## The Simulator

The first step is to download the simulator build that's appropriate for the operating system. Here are the links for [Linux](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip), [Mac](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Mac_Roversim.zip), or [Windows](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Windows_Roversim.zip).

The simulator can be tested by opening it up and choosing "Training Mode". Use the mouse or keyboard to navigate around the environment and see how it looks.

## Dependencies

Python 3 and Jupyter Notebooks are needed to do this project. 

If you are not familiar with these dependencies here is a great link for learning more about [Anaconda and Jupyter Notebooks](https://classroom.udacity.com/courses/ud1111).

## Recording Data

Although, files were saved in test_dataset, they are massive in terms of uploading to GitHub. 

In order to record data, firstcreate a new folder to store the image data in. Then launch the simulator and choose "Training Mode" then hit "r". Navigate to the directory to store data in, select it, and then drive around collecting data. Hit "r" again to stop data collection.

## Navigating Autonomously

The file called drive_rover.py is what will be used to navigate the environment in autonomous mode. This script calls functions from within perception.py and decision.py. The functions defined in the IPython notebook are all included inperception.py.

drive_rover.py should work as is if you have all the required Python packages installed. Call it at the command line like this:

python drive_rover.py
Then launch the simulator and choose "Autonomous Mode". The rover should drive itself now! It doesn't drive that well yet, but it's your job to make it better!

_Note: running the simulator with different choices of resolution and graphics quality may produce different results!_

