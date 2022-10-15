# Eyeauthentication

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

# Installation 
WINDOWS: an anaconda environment .yml config file has been provided for easy dependency installation. 