# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Marco Korcak

Time spent: 4 hours spent in total

Link to project: (https://glitch.com/edit/#!/cut-incandescent-microwave)

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

- [X] User is alerted and gets a notification when they make a mistake saying how many mistakes they have made

## Video Walkthrough

Here's a walkthrough of implemented user stories:

The gif below shows the user losing and making mistakes

![](https://i.imgur.com/6S8eAWu.gif)

The gif below shows the user winning the game

![](https://i.imgur.com/lCrn3x7.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
 
 When doing this work I had trouble working with the images and sizing them so I used w3schools for reference to get an idea of how to approach the problem. Link: https://www.w3schools.com/cssref/css3_pr_background-size.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

After completing the pre-work I can say that one challenged I encountered was getting the program to produce a random pattern each time it ran. This was an issue because I had difficultly altering the existing code at first. I understood that the sequence array needed to be empty because if it had set values then it would not be able to change. I had to create another variable that defined the length of the array which set bounds for the code as to how many different numbers needed to be generated in one round. Then I had to work with the Math.random function which was not that difficult since all I needed to do was define a new function and define the maximum and minimum number. I used a for-loop so there were multiple random numbers generated and set the bound as less than the pattern length instead of a definite number in case the pattern length was changed. A for loop was used to generate a different number for each “i” or each new round that the user progressed. I overcame this issue by understanding the fundamentals of the issue and realizing that a function was needed to create the new sequence and then it needed to be called in order to put it to use. Understanding the issue and logic was what allowed me to progress and overcome this issue.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

This work has led me to wonder many things about web development. To start off, I wondered how developers keep their code organized since they need to manage HTML, CSS, and JavaScript files with many lines of code. Is there a certain method of organization that is used and how is the data gained from the user stored? I wonder that when websites gain data from the user how is it then stored and used to improve the website? Moreover, this project has also led me to wonder about the visual aspect of web development and how are animations implemented in websites without causing the website to slow down or crash. I am curious as to how complex animations or multiple images are used in a way that does not hinder the performance of the website. Lastly, I wonder about safety and privacy. I wonder how data is received from the user in an ethical manner that benefits the platform but does not invade the privacy of the user.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project I would make numerous changes. Firstly, I would edit the visuals of the project. I would add a detailed description of the game so user can easily understand what to do before actually starting the game. Moreover, I would change the logic of the game so there is an option where the user can choose how many buttons there are. This in a sense would allow the user to increase of decrease the difficulty of the game. Additionally, I would use the CSS aspect of the project to implement animations that when the user wins, animations such as fireworks or confetti appear to signify that the user won. I would also create a place where the user can leave a rating of the game and any recommendations that they have. I would create a data base where user responses are stored for future reference and use that to improve the game. In essence, I would change certain aspects of the project to make it user friendly and easily understandable.



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
