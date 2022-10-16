## Eye Blink Authentication System

An opencv project for using the blinking of eyes as a password

Some people type words for their password. This script is a proof of concept that uses a camera and opencv to let you use your eye blink as a password.

An example password: 'LRB'

Each digit can be either:
	'L': Left eye closed
	'R': Right eye closed
	'B': Both eyes closed

The password length can be as long as desired. 
To unlock the password:

1. Hold left eye closed, right eye opened
2. Open both eyes (locks in the left eye closed digit)
3. Hold right eye closed, left eye opened 
4. Open both eyes (locks in the left eye closed digit)
5. Hold both eyes closed 
6. Open both eyes (locks in the left eye closed digit)

And the password has matched and the script will exit. It is up to you to decide what actually gets unlocked. 

### Installation 

WINDOWS: an anaconda environment .yml config file has been provided for easy dependency installation. 

SOFTWARE SPECIFICATIONS -
 
 - OS : Windows 10
 - IDE: Anaconda 3 2020.02
 - Python Version : 3.7 recommended

HOW TO USE THIS SOFTWARE -

1. Download Anaconda from the below link
https://repo.anaconda.com/archive/Anaconda3-2020.02-Windows-x86_64.exe
2. Install the downloaded Anaconda application.
3. Click on start, and search for Anaconda Prompt and click on it.
4. Enter the following commands in the anaconda prompt cli to install few packages.
 -  conda update conda
 -  conda create -n myenv python=3.7
 -  conda activate myenv
 -  conda install -c conda-forge dlib
 -  conda install pip

 -  pip install imutils
 -  pip install scipy
 -  pip install opencv-python
 -  pip install matplotlib
 - (if still any error occurs saying ..package not found, then type this command - pip install (name of the missing package))
 
 5. Through the commands, go inside of your project folder (eg: ... , cd Eyeauthentication)
 6. Type python eyeBlinkPassword.py and ENTER. 
