# Pre-work - *Dazzler: the Sound Memory Game*

**Dazzler** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **PAVIT BAGGA**

Time spent: **6-7** hours spent in total

Link to project: (https://sponge-flashy-auroraceratops.glitch.me or https://glitch.com/edit/#!/sponge-flashy-auroraceratops)

## Required Functionality

The following **required** functionality is complete:

* ["Dazzler: the Sound Memory Game" ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [yes, I did this path i had to make use of Dom to hide the button ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [for this I made use of buttons.active and buttons.lit to implement the functionality] Game buttons each light up and play a sound when clicked. 
* [this is the cluepathsequence method which i implemented following the guidelines] Computer plays back sequence of clues including sound and visual cue for each button
* [so for this each time the guess was correct the progress was incremented by 1] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [if user guesses all the buttons correctly then it prompts that user has won] User wins the game after guessing a complete pattern
* [if any guess is wrong then it prompts the user has lost] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [No, I just followed the guidelines] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [I implemented more frequencies] Buttons use a pitch (frequency) other than the ones in the tutorial
* [I created 7 buttons in total] More than 4 functional game buttons
* [ I tried lowering the speed via clueHoldTime ] Playback speeds up on each turn
* [ I implemented this but I was having some errors so it is just commented] Computer picks a different pattern each time the game is played
* [I could not implement this ] Player only loses after 3 mistakes (instead of on the first mistake)
* [I could not implement this ] Game button appearance change goes beyond color (e.g. add an image)
* [I could not implement this ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [I could not implement this ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)
![codepath]

If you recorded multiple GIFs for all the implemented features, you can add them here:
![] 
![codepath](https://user-images.githubusercontent.com/78366183/161368888-d30e6d40-0484-476b-8f38-cda6e86423ed.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
No, I did not use any outside resources. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
so the challenge that i encountered in creating this submission is in the guess method first I was tried it by myself and some where it was partially working 
so as I am used to c++ i placed brackets pattern.length() instead of pattern.length so this took me some time

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
 After completing my submission I feel I have learnt alot regarding webdev. Firstly, I made use of 3 different types of languages to create one Application.
 1) The questions I have is that if we can integrate atleast 3 programming languages such as Html,Javascript, and css can we also integrate it with java and c++ or python to have multiple/advanced functionalities?
2) How advance can I make my webpage using only these three languages?
3) How are we able to make use of online compilers and IDE such as GLitch when it mostly uses Html, css and javaScript
 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
IF I had a few more hours to work on this, I would spend my time correcting the errors of random secret sequences as Somehow at the end they were
giving me some errors. Moreover I wanted to implement different css styles to the layout of my game. Also, I wanted to set a time limit and add levels to the game to make it interesting and harder each time. FurtherMore I wanted to add images to my buttons.


## Interview Recording URL Link

[My 5-minute Interview Recording](https://asu.zoom.us/rec/share/AMko3VQAU1w4kAZ0InbXIY840Y5FZukZ7JpM20edUqH-OQ1JADj7PINySJ1AKU0a.gHg8KZ--2add7ZMz?startTime=1648879958000)


## License

    Copyright [PAVIT BAGGA]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
