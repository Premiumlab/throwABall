# Throw a Ball
Implement a VR game where users can throw a ball and switch modes of different physics environment. 


Create a VR prototype with a ball throwing task. 

## The user is able to pick up balls placed on the ground, which should have an assortment of different masses.  
Darker color balls have heavier weight.

## The user is be able to switch between the different behaviors using a controller button.

Three possible physics behaviors: null, semi-normal, or normal.
  Null behavior: 
    The ball could be moved while it was in contact with the hand, but it would never roll or maintain momentum once out of contact with the hand.
  Semi-normal behavior:
    The ball would behave normally 50% of the time, and not move 50% of the time.
  Normal behavior:
    When the ball was picked, the physics engine was used to determine the path of the ball.
    


This project is designed for Oculus Rift. 

Third party used:
Oculus SDK, OVRPlayerController, OVRCameraRig, LocalAvatar, OVR Grabbable, OVR Grabber
