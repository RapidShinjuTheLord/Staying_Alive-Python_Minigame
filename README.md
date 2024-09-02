# Staying_Alive-Python_Minigame
Fully playable minigame used as the basis for my reinforcement learning project! Use the arrow keys to dodge the obstacles for as long as possible. 
Most obstacles have a non-dangerous "Warning" state, use these to your advantage.

For more information about the full project, feel free to watch the video:

[![Making an AI to play my game for me](https://img.youtube.com/vi/NZcOcnKrRLk/0.jpg)](https://www.youtube.com/watch?v=NZcOcnKrRLk "Making an AI to play my game for me")

![alt text](media/Artwork/pdown1.png) ![alt text](media/Artwork/pleft1.png) ![alt text](media/Artwork/pright1.png) ![alt text](media/Artwork/pup1.png)

There are several different types of obstacles, including lasers, fire, plasma balls, and bombs. Other than the plasma balls, all obstacles are indicated with a flashing light before appearing, so pay attention to these signs. In general, it is not difficult for human players to outperform AI agents.

Both pygame and openai gym will be needed to run this project, as it was also used as an environment for Reinforcement learning agents to train on, with reward functions and environment states. Simply run main.py to use the project.
