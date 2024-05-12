The deployed version is also present: https://media-player-main.vercel.app/

Steps and Commands to run this project:
1) Install all node modules :
   command -> npm i
2) Run the project
   command -> (a) npm run build

   (b) npm run start or use npm run dev

In this project, when we maximize the screen press two times Esc key, in order to get the normal screen.

The key features of this project: 
 The player is capable of distinguishing between audio and video URLs and adapt its functionality accordingly. The required controls are as follows:
1) Play/Pause

2) Previous

3) Next

4) Volume Control

5) Minimize

6) Full Screen

7) 10 seconds Forward

8) 10 seconds Backward

9) Play Speed Control (0.5x to 4x) on 0.25 interval

10) Progress Bar indicating media progress

11) Display media duration and current progress on the progress bar
   
12) Enable media playback from any clicked position on the progress bar 

13) Implement keyboard accessibility as follows:
Up/Down Arrow: Volume Control,

Right/Left Arrow: 10-second Forward/Backward, 

F: Full Screen, 

Esc: Exit Full Screen, 

W: Minimize, 

N: Play Next Media, 

P: Play Previous Media, 

15) Automatically hide controls unless hovered over or the player is paused
    
Additional Details:
1) Minimized player should transition to a fixed floating box at the bottom right corner, maintaining a 16:9 aspect ratio with 300px width
2) Minimized box should include a close and expand button
3) Tech Stack : Next.js, CSS, Zustand

Talking about bug in the project:
1) Spacebar functionality not working properly
2) Mute using "m" keyword is also not working properly

Project Output: 

![Screenshot (2959)](https://github.com/nancyy24/media_player/assets/93393288/a906d5e7-89fb-41e5-89be-2153dd29ade3)
![Screenshot (2958)](https://github.com/nancyy24/media_player/assets/93393288/7d60a5c8-ddcd-4070-a231-1544a50db6a3)
