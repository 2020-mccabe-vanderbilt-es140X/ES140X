# Welcome to ES140X

Below are set of instructions to help you effectively participate 
in this class, ES140X: Introduction to Engineering. 

- [Watch videos on Brightspace](#watch-videos-on-brightspace)
- [Download this repository](#download-this-repository)
- [How to open your terminal](#how-to-open-your-terminal)
- [Set up your Anaconda environment](#set-up-your-anaconda-environment)
- [Access an assignment or class in Jupyter](#access-an-assignment-or-class-in-jupyter)
<br />
<br />
<br />


## Watch videos on Brightspace

We have created a few videos to assist with some of the set up steps. The videos are hosted on Brightspace under the Videos section of this class. We recommend that you watch through the videos in order first to get an understanding of what you need to be doing here. Then, continue through this document and replicate what has been shown in the videos, using them as a second source.
<br />
<br />
<br />

## How to open your terminal

#### MacOS
You can open the terminal application on MacOS by either:
1. Use Spotlight search: press “Command + Space” and search for “terminal”
2. Open Launchpad and look for the “Terminal” app


## Download this repository

This repository contains software and files neccessary for activities in this class, so we ask you to download this repository and put it in a location convienient for later reference. We recommend you put it in your home directory using the commands below:  
`cd $HOME`  <br/>
`mkdir ES1403_class` <br/>
`cd ES1403_class` <br/>
`git clone https://github.com/2020-mccabe-vanderbilt-es140X/ES140X.git` <br/>
<br />
<br />
<br />

## Set up your Anaconda environment

Anaconda is a free, open-source distribution of the Python and R programming language for scientific computing, that aims to simplify package management and deployment. In this class, we will use Anaconda to manage our Python environment. Below are short instructions to set up the Anaconda software for Mac.

#### MacOS  
1. Download miniconda from:   
    https://docs.conda.io/en/latest/miniconda.html   
    (Select the correct installer for **Python 3.8, 64-bit pkg**)
2. Install miniconda from the downloaded file  
3. In your terminal, download and change into this repository (ES140X).
If you followed the above [instruction](#Download-this-repository) and put this repository at your home directory, you can change into that folder by  
`cd ~/ES140X`
4. If you don’t know how to do this, make sure you watch the video labeled `classroom_walkthrough.mp4` from Brightspace before continuing.
5. Create and activate a new conda environment by typing in the terminal window:
    `conda env create -f environment.yml`  
    If prompted you may need to update your conda environment and rerun the above commands.
6. When the command has successfully executed then type:  
    `conda activate class37`   
**Note:** You will need this command whenever starting up a new terminal to access the class materias


## Access an assignment or class in Jupyter

1. Follow the link that will be sent out through email to a specific assignment. Accept the assignment, and let a copy be made to your GitHub account. 
**Note** from time to time, accepting the assignment will work, but the green bar will not complete and notify you that your copy is ready. Don't worry about it, as soon as you hit accept, the assignment will be available to you. Exit from that browser window, and in a new one navigate to your GitHub account. Under the 2020-mccabe-vanderbilt-es140X classroom, you should be able to find all of your assignments. It can be found from your GitHub homepage, in the left column under organizations. 
2. Once on your repositories GitHub page, look for a large green button with **Code** in white letters. Click on it to open a drop down box, and copy the URL that is there. 
3. In a terminal window, use the `cd` command to navigate to the ES1403_class directory. It should be located at ~/ES1403_class.
4. Run the following command: `git clone the-url-you-just-copied`. This will make a local copy of the repository at GitHub.com. 
**MAKE SURE YOU ARE NOT IN THE ES140X DIRECTORY WHEN YOU CLONE A NEW REPOSITORY. JUST CLONE IT TO THE ES1403_class DIRECTORY.**
Use `pwd` to check what directory you currently are in.
5. Use the `ls` command to view all of the files in that directory, and you should see a new directory titled the same as the repository you just copied.
6. `cd` into the cloned assignment you just installed. If you don’t see the assignment on your local machine, watch the `classroom_walkthrough.mp4` video for additional help.
7. Type `jupyter notebook` into your terminal
8. The jupyter notebook will be open as one tab in your default browser  
If this doesn't occur automatically, look a the output from your jupyter notebook command. You should see a web link that looks something like `http://localhost:8888/?token=fd014533bc5780c313dfd1803838a89c6a90cdcd75d0cb2b` Copy that link by highlighting it and using ctrl-c. Then, paste the link into the web browser of your choice. We recommend Google Chrome.
9. Click on folders to navigate through them, or on files to open them. Text files will open with a built in text editor. Jupyter notebook files have the extension .ipynb. These are the files where you execute python code, and where we'll run are assignments from.



