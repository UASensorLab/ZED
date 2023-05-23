# ZED
To see our quick start guide, go to sensorlab.arizona.edu > Equipment > Equipment Resources > Zed2

These are example files from the ZED website (https://www.stereolabs.com/docs/tutorials/) with modifications to make them more user-friendly.

Image Capture: The original ZED tutorial captures 50 images but doesn’t save them. Our image_capture.py file allows you to capture JPG images or numpy arrays and save them with timestamps in their names.

Depth Perception: The original ZED tutorial prints the distance of the object in the center of the camera’s view 150 times, but it doesn’t save any data. Our depth_sensing.py file allows you to save depth data into a CSV file.

Camera/Positional Tracking: This ZED tutorial prints translation, orientation, acceleration, and velocity data but doesn’t save it. Our positional_tracking.py file allows you to save this data to a CSV file.

If you try running Python starter code and get the error "ModuleNotFoundError: No module named 'pyzed'", you’ll need to install Anaconda and open any ZED scripts in a Python environment with the built-in libraries defined by ZED_Env_Anaconda.yaml.
