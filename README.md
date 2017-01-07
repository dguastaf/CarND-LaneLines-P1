#Finding Lane Lines on the Road
*Project 1 of the <a href = "https://www.udacity.com/drive" target="_blank">Udacity Self-Driving Car Engineer Nanodegree</a>*

In this project I wrote a simple algorithm to detect lane lines on the road using Python and OpenCV.
The algorithm reads a video, uses computer vision to detect where the lane lines exist, and then draws two red lines to show their locations. 

**Output:**  
<img src="assets/output/white.gif" width="500" alt="Example output"/>

The project's source is written in a Jupyter Notebook, [P1.ipynb](P1.ipynb). See ["Building source"](#building-source) if you want to build & run the code.

This project is meant as warmup and is not anywhere close to production ready. We will implement a more robust solution in a later project. 

##Building source
All code is contained within a Jupyter Notebook.

Choose the appropriate Python 3 Anaconda install package for your operating system <a href="https://www.continuum.io/downloads" target="_blank">here</a>.   Download and install the package.  

After installing Anaconda type these commands  
`>  conda create --name=LaneLines python=3 anaconda`  
`>  source activate LaneLines`

Double check you are in your Python 3 environment:
`>python`    
`Python 3.5.2 |Anaconda 4.1.1 (x86_64)| (default, Jul  2 2016, 17:52:12)`  
`[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.28)] on darwin`  
`Type "help", "copyright", "credits" or "license" for more information.`  
`>>>`   
(Ctrl-d to exit Python)

Next run the following commands at the terminal prompt to get OpenCV:  
`> pip install pillow`  
`> conda install -c https://conda.anaconda.org/menpo opencv3`

Then to test if OpenCV is installed correctly:

`> python`  
`>>> import cv2`  
`>>>`  
(Ctrl-d to exit Python)

Install moviepy  

`>pip install moviepy`  

and check that the install worked:

`>python`  
`>>>import moviepy`  
`>>>`  
(Ctrl-d to exit Python)

Finally, open the code in a Jupyter Notebook

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook to complete the project.  

If you are unfamiliar with Jupyter Notebooks, check out <a href="https://www.packtpub.com/books/content/basics-jupyter-notebook-and-python" target="_blank">Cyrille Rossant's Basics of Jupyter Notebook and Python</a> to get started.
