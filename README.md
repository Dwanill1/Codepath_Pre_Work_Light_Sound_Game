# Codepath_Pre_Work_Light_Sound_Game
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Dhwanil Nikunj Mehta

Time spent: 6 hours spent in total

Link to project: (https://dhwanil-nikunj-mehta-light-sound-game.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [Yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Yes] Game buttons each light up and play a sound when clicked. 
* [Yes] Computer plays back sequence of clues including sound and visual cue for each button
* [Yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Yes] User wins the game after guessing a complete pattern
* [Yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Yes] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Yes] Buttons use a pitch (frequency) other than the ones in the tutorial
* [No] More than 4 functional game buttons
* [No] Playback speeds up on each turn
* [No] Computer picks a different pattern each time the game is played
* [No] Player only loses after 3 mistakes (instead of on the first mistake)
* [No] Game button appearance change goes beyond color (e.g. add an image)
* [No] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [No] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
https://media.giphy.com/media/Ehei2VYc3Mg9dXnyYT/giphy.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I faced in creating this submission is creating the playClueSequence() function. My code was making the buttons work and change the light as well as the audio was working when clicking the buttons. However, when I finished working on the playClueSequence() function, the game was not displaying the clues even though I followed the instructions given in the pre work. I followed a traceback procedure, from one function to another to check what function was affecting the error but was not able to figure it out.
I went through a more elaborate debugging process then. I tested every single function which was a part of this program and commented out the others to check the function. I then was able to narrow the functions which caused the issued to playClueSequence(), playSingleClue(), lightbutton() and clearButton(). After this, I went back to reading the pre work more carefully again and I found this mistake to be in the lightbutton() and clearButton()  functions. I had put the wrong button name in the functions. This made the functions not use the correct button ID to add the clues in the game. I changed the button name to the one in the html function and the playClueSequence() function started to work efficiently.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing some front-end web development coding in this pre work some questions have come up in my mind. First, are data structures in web development? If yes, it only used for backend or can it be used in frontend as well. Another question which came up is whether css, javascript and html are best used if used together or are they better to be used individually are they better to use? Another question which came up is how can I connect a database to a web app? How are frameworks like React, Node.js and more being currently used in the process of web development? Another question which came up was whether web development is only limited to websites or other web applications as well? These are all the questions which came up for me. I’m sure more questions will come up because web development is a broad form of development and it is fun learning about it.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours on this project, I would definitely work on adding more features in the project. I would love to add more design to the project to make it look better. I would create a function which randomly selects patterns every time a user starts the game. I would add a feature which allows the user to decide the pace they want for the clues to come as well as the choice of the colors. I would also work on adding various audios to the game making it more fun to learn about it. I would work on editing the playClueSequence() function which would give clues in different ways as well. I would also add more buttons to the game making it more interesting to play with. 



## Interview Recording URL Link

[My 5-minute Interview Recording] https://drive.google.com/file/d/1jncZyc0hAYf3F7QtkGjMlp3XpZcevtwy/view?usp=sharing


## License

    Copyright [Dhwanil Nikunj Mehta]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
