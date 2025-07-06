# iCAMP (Demo Version)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/djg6565/icamp/blob/main/src/OpenPose-OpenCV.ipynb)


iCAMP (Integration of Computation, Analysis, Mathematics, and Playing) is a software that is a fusion of computational physics and AI. Using the OpenPose, OpenCV, and YOLOv8 models, it analyzes videos of the user's basketball shots and automatically provides feedback on how to improve.

This is a demo version that is intended to showcase the core abilities of iCAMP. However, more is to come in the full release, which is scheduled for August 2025.

## Installation

Download this repository as a .zip file. If not already installed, please install Conda (either Miniconda or Anaconda) here: https://www.anaconda.com/download/. Follow the instructions on that website/on the installer.

Create a Python 3.9 environment by running the following: 
```
conda create -n py39_env python=3.9
```
Then, activate the new environment,...
```
conda activate py39_env
```
...change directory to where the repository folder is located locally, and install dependencies:
```
pip install -r requirements.txt
```
Note that if you are using Windows, you must also install Xming.

Next, Jupyter needs to recognize py39_env as a kernel. This can be done with
```
conda install ipykernel
```
```
python -m ipykernel install --user --name test --display-name "Python 3.9 Environment"
```
or whatever display name you would like.

Once installation is complete, activate Jupyter notebook:
```
jupyter notebook
```
## Usage
To open the program again, activate py39_env, change directory to iCAMP, and run it in Jupyter.

FOR NOW, ONLY FREE THROW SHOTS WITH THE CAMERA AT THE SIDE OF THE PERSON WORK. A sample video has already been provided in the folder named "UPLOAD VIDEO HERE." For demonstration purposes, only use this video, as the program seems to struggle with some other ones.

Navigate to the "src" folder and open "OpenPose-OpenCV.ipynb". Change the kernel (in the top right corner) to "Python 3.9 Environment," or whatever you named the kernel earlier. Then, run all of the cells.

On first use, expect a delay before the program initiates as Jupyter loads the environment.

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
