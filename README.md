# ai_training

## Setting up Python with Anaconda
Please install Anaconda (Python 3.7) from this [link](https://www.anaconda.com/distribution/). <br>
Download the appropriate version based on the operating system. The installation should be straight-forward, however, more details can be viewed [here](https://docs.anaconda.com/anaconda/install/). <br>
Again, choose the right instruction based on the operating system.


## Setting up Python with Miniconda
Please follow these instructions:

1. Browse to miniconda download page [here](https://docs.conda.io/en/latest/miniconda.html)
Download the installation file for python 3.7 version and the operating system you are using.   
2. Install the package.
3. Now it is time to create a new environment with the required packages. On windows, open Anaconda Prompt from Start Menu, and type the following command and hit enter:<br>
```conda create -n myenv python=3.7 jupyter keras matplotlib numpy pandas scikit-learn tensorflow```<br>
On OSX or linux, open a terminal and type in the above command.<br>
Also, if you prefer to use Spyder as Python IDE, add “spyder” at the end of the above command.<br>

This should be it. You can close this window until we get back to it in the workshop.
