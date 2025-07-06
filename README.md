# iCAMP (WIP)

iCAMP (Integration of Computation, Analysis, Mathematics, and Playing) is a software that is a fusion of computational physics and AI. Using the OpenPose, OpenCV, and YOLOv8 models, it analyzes videos of the user's basketball shots and automatically provides feedback on how to improve.

This is a work in progress.

## Installation

If not already installed, please install Conda (either Miniconda or Anaconda) here: https://www.anaconda.com/download/. Follow the instructions on that website/on the installer.

Create a Python 3.9 environment with Tensorflow by running the following: 
```
conda create -n tf_py39_env python=3.9
```
Then, activate the new environment,...
```
conda activate tf_py39_env
```
...change directory to where "iCAMP" folder is located, and install dependencies:
```
pip install -r requirements.txt
```
Once installation is complete, activate Jupyter notebook:
```
jupyter notebook
```
iCAMP is now ready to run!
## Usage
To open the program again, activate tf_py39_env, change directory to iCAMP, and run it in Jupyter.

Upload a high-resolution clip to the folder named "UPLOAD VIDEO HERE." This clip must be a .mp4 file and be named "video.mp4". Ideally, it should be 30 fps, well-lit, and have been shot to the side of the person and slightly in front with the entire person in view. Please be sure only one person is in the shot. For development purposes, a sample "video.mp4" is already included.

Navigate to the "src" folder and run "OpenPose-OpenCV.ipynb". This will run iCAMP.



## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright © 2025 Derek Guo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

**Third-Party Code (Apache 2.0):**  
This project includes modified code from:  
- **Project:** Human Pose Estimation with OpenCV  
  **Repository:** [github.com/quanhua92/human-pose-estimation-opencv](https://github.com/quanhua92/human-pose-estimation-opencv)  
  **Original Author:** Quan Hua  
  **Modifications:**  
  - none


See NOTICE for a copy of the Apache 2.0 license.