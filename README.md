# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Marco Korcak

Time spent: 5 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/cut-incandescent-microwave)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] User is alerted and get a notification when they make a mistake saying how many mistakes they have made

## Video Walkthrough

Here's a walkthrough of implemented user stories:

The gif below shows the user losing and making mistakes

![](https://i.imgur.com/6S8eAWu.gif)

The gif below shows the user winning the game

![](https://i.imgur.com/lCrn3x7.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
 
 When doing this work I had trouble working with the images and sizing them so I used w3schools for reference to get an idea of how to approach the problem. Link: https://www.w3schools.com/cssref/pr_background-image.asp 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

After completing the pre-work I can say that one challenged I encountered was getting the proghram to produce a random pattern each time it ran. This was an issue because I had difficult altering the existing code at first. I understood that the sequence array needed to be empty because if it ihad set values then it would not be able to change. I had to create another vairable that defined the length of the array which set bounds for the code as to how many different number nbeeded to be generated in one round. Then I had to work with the Math.random function which was not that difficult since all I needed to do was define a new function and define the maximun and minimum number. I used a for-loop so there were multiple random numbesr genereated and set the bound as less than the pattern length instead of a definite number in case the pattern length was changed.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]



## License

    Copyright [Marco Korcak]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
