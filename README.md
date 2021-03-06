# Super Puzzler
## VR Puzzle Game

### Summary
This project was created for the Udacity VR Design traning. This repo is geared for documenting the process
That I took to create, test, and iterate on the project. The final product is a puzzle game where the players
can go into a dungeon and will be greeted with orbs that play a sequence of sounds. These sounds then need to be clicked
backed in the same sequence. If the player is successful then the player will be exited out of the game.

The project took about 9 - 10 hours to complete. From idea creation, sketching, user testing, game design, iterating on design and scripting I had a lot of fun with this project

[Final Project Video](https://www.youtube.com/watch?v=havos3ysGOE "Final Project Video")

### Persona
The persona I focused on for this project was a user who was either new to VR or had a few experiences with it. I also wanted to find a age group that was slightly older
as the theme and mood of the game was a little gloomy. The persona I decided on is as follows

NAME: Anabell
AGE: 25
VR Experience: Low to Medium

Based on my user test, my assumption for choosing a older person seem correct.

### Sketches

Inital sketch of the design for the game

<img src="https://github.com/soctkoren/VrDesignProject/blob/master/images/sketch1.jpg" width="400">

Inital sketch of the GUI for the game

<img src="https://github.com/soctkoren/VrDesignProject/blob/master/images/gui.png" width="400">

Based on my user test, I had to add a few subtitles and warnings to tell that the user will move when the start button is hit.

### User Testing

## First Test

![inital level](./images/inital-level-design-pre-bake.png)

This test was to see how the inital design and scale of the room felt for the user

User Testing Notes:
Name: Chimi Kim
Experience in VR: Low

Question 1: Tell me about the room size.
Answer 1: The room looks scary, but well lit. The Size of the room seems good, but I feel a little shorter than I normally am.

Question 2: Tell me about the objects you see.
Answer 2: Most of the items are interesting. The barrels are cute, but the little ones look very small. I also noticed the orbs right away. Not sure what they do but they are cool. 

Question 3: Is there anything wierd you notice about the room.
Answer 3: Not really. I don't see anything through the doors. So I actually don't know which way is front or back.

Question 4: If there is one thing you would want to change or add what would it be?
Answer 4: I would change the color of the blue light to pink or purple. 

![after bake](./images/after-bake.png)

#Analysis of User Test:

The user seems to be interested in the vr experience, however, this is her 2nd vr experience so the bar is pretty low.
One interesting thing is that the user is able to detect their own height very clearly and commented on that difference based on the
room size. The orbs was another interesting thing that user pointed out. Because of the spot light it was obvious that something needed
to be done with it, but at this point of the game they are not really interative so the suer was confused.

ACTIONS TAKEN: I've re-size a few items and moved the camera a bit down. I did not change the lighting per user testing as I wanted to keep a more darker theme to match my persona.
## Second Test
This test was to see how the inital design of the user interface

![before user](./images/before-user-test.png)

User Testing GUI Notes:
Name: Andrew Keturi
Experience in VR: Medium

Question 1: Do you see any canvas? 
Yes, I see a black canvas. It looks like a welcome message and a start gui

Question 2: How do you think you can interacte with the screen?
I like how the pointer is green and when I interacte with what looks like the button, it highlights in a light green color. Very similar to
how websites would work. If I click on it it would probably start the game

Question 3: Tell me about the canvas, is there anything you would change about them?
Hmm the I don't really like the black canvas. It's very bland. It is also a little big and I wish I can see part of the game behind it.

Question 4: Click on the start button, and tell me about the new canvas.
The new canavs looks like it's there to restart the game. Pretty straight foward.

#Analysis of User Test:

The user was able to locate the gui easily. Also the user mentioned that the gui is a little boring so maybe adding some color would lighten things up

ACTION TAKEN: The main thing I changed was the color for the canvas. I did agree with the user that the screen was a little borning. Also the green theme made sense.

![after user](./images/after-user-test.png)

## Third Test
This test was to gauge the movement experience for the user.

[Before User Test Video](https://www.youtube.com/watch?v=BWD9LF8Y_eM "Before User Test Video")

User Testing Movement Notes:
Name: Chimi Kim
Experience in VR: Low

Question 1: Click on the start button and tell me how you feel?
I movement was a little jarring because I didn't expect myself to move foward

Question 2: How is the speed. Too fast or too low?
The speed was a little fast but not too bad

Question 3: Are you feeling any discomfort?
I only felt a little discomfort in the begining when I didn't know what was going to happen. 
It would be nice if the game told me I was about to move foward when I did something.

Question 4: would you change anything about the experience?
Not much, just what I mentioned about the speed and a little heads up on when I'm going to move.

#Analysis of User Test:

The user not knowing what the start button did was not a good user experience. I will add further instructions so that the player knows what will happen when they hit start.
Also I will slow down the movement speed.

ACTION TAKEN: I lowered the speed of the player. I also added subtitle instructions on the fact the the player will be moving foward when they hit start.

[After User Test Video](https://www.youtube.com/watch?v=RmOa4UJySrU "After User Test Video")

## Fourth Test
This test was to test out the beta version of the product

User Test Beta
Name: Chimi Kim
Experience in VR: Low

Question 1: Start the game and tell me if the movement feels good and tell me about the play area.
Now that I see the instructions telling me that I'm going to move foward. I feel like the movement is a little slow. 
Since I'm expecting it now, I rather speed up the movement and get to the play area faster. The play area is very gloomy but I like that

Question 2: Do you enjoy the sounds in the game?
Yes, but the audio seems a little loud for some of the sound effects

Question 3: How was the overal experience playing the game.
It was fun and interesting. I like how a lot of the problems I addressed in earlier version of the game was fixed. Nice job.

ACTION TAKEN: After reviewing the user testing notes. I adjusted the speed of the player movement to be faster so that the players can get to the action more quickly. I also lowered the sounds.

[Project Demo](https://www.youtube.com/watch?v=havos3ysGOE "Final Project Video")

### Breakdown For Final Project

![start](./images/breakdown_start_stage.png)

At the start stage of the game, the player is greated with a nice green welcome screen. The screen instruct the use to hit start to
move foward to the game. After the user hits start the GUI disappears.

![play](./images/breakdown_play_stage.png)

In the play area, the user is given a challenge. The balls will make a pattern of noise. The user needs to select the same sequence
as the puzzle in order to beat the game. If the user gets the sequence incorrect, the user will be alerted with a error sound. Afterwards the sequence will
be played again. Once the user gets the correct sequece, a success sound will play and the user will be moved foward


![restart](./images/breakdown_restart_stage.png)

In the final restart screen. The user is instructed to try again. Much simlar to the first stage of the game, once the user hits the restart button
the player will be moved back to the start of the game, where the game will re inital and the start screen will appear once more.

### Conclusion Sections
This project was very insightful. The project made me think about a lot of aspects of vr development that I previously did not think about. 
The lessons learned regarding player movement and players feeling motion sickness is great way to start thinking for VR development. I particular enjoyed having
my wife play with the app and getting her to talk about something I was building and be part of the iterative process. Also the persona helpped me keep the mood different from
what I would have normally created. I would have made the app very happy and not gloomy as I personally don't like scary games or videos. However my persona was a person who likes scary
movies and puzzles so this helped keep the mood nice and gloomy. Another aspect that was interesting was the GUI. I actually really liked how the GUI felt very similar to a 
web interface. Especially the onhover or onGaze felt very natural and intuitive. Although this project was geared toward scripting, but I did have to fix quiet of bit of code
to get the project to function properly. This was good and bad I think. While it allowed me to practice my scripting, it did take 