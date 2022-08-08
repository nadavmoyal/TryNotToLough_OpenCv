
![alt text](https://img.wallscloud.net/uploads/cache/3378068484/despicable-me-2-laughing-minions-lxy5-1024x576-MM-90.webp)

# TryNotToLaugh_OpenCv
A computer game based on python opencv
# Python opencv project:
>Made by Nadav Moyal.  

## Introduction:
This project is a camera pc game based on python opencv.  
This project is a self-made project that uses a camera, face recognition technology and "laugh detector" algorithm. 

## Game description:
The game simulates the "Try not to laugh!" Challenge.  
A funny video is shown on the screen, and the player's goal is not to laugh or smile.  
The player has an HP scale, and whenever the player laughs - his HP is reduced accordingly.  
The calculation of "Is the player laughing?" Is made by an algorithm.
If the player was able to watch the whole video to the end - he  won!
Otherwise he lost the challenge.

### The "Laugh Detector" algorithm:
The algorithm calculates the relative distance between the player's mouth points.
In case the player laughs - it means that the distance between the points of his mouth increases.
So the algorithm finds the moment when the player's mouth is open by a size greater than the fixed average distance.
And when it reaches a certain distance we know the player is laughing.

## Game rules:
>Do not turn your face away from the screen
>Do not cover your mouth with your hand
>Try not to smile or laugh

## Operating Instructions:
1. Download all the files.  
2. Install `cv2` , `cvzone` and `pygame`:   
3. Put the files in the same folder.  
4. In the command line, write the following command:  
5. `python main.py`  or `python3 main.py`
6. Start playing  ! !  



