# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ahmed Elsharkay**

Time spent: **4** hours spent in total

Link to project: (https://glitch.com/edit/#!/versed-coffee-seer?path=style.css%3A1%3A0, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [* ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ *] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ *] Game buttons each light up and play a sound when clicked. 
* [* ] Computer plays back sequence of clues including sound and visual cue for each button
* [ *] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ *] User wins the game after guessing a complete pattern
* [ *] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/AR4hjuHrva.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[none]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The first challenge that I encountered in creating this submission is dealing with Javascript because I have never seen any javascript code before. It took me some time to know what does quantities like document and do and what is used for, I had to go to the StackOverflow website and read about them to understand them. Also, the if statements at the end of the program were hard for me to do in javaScript, I did similar if statements but in c++ and then I saw the equivalent code for them in javascript. The second challenge I encountered was some code lines in CSS that I didn't see before like button1:active. even though I took a crash course in CSS, but I didn't see this one(button1:active ) before. However this one was the first time a little bit easy, I didn't have to read about it in outside resources because it was so obvious to understand the functionality of it.  ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[does the frontend engineer do the javascript programing ? ]
[does the backend engineer do the html and css programing ?]
[do we use PHP in the databse of the website?]
[does the full stack engineer able to do a website by his own?]
[how long will it take me to be a professional web developer?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I wolud try to make the computer picks a diffrant pattern each time, I don't know how to do this in javaScrpit, but I think that I can use a funciotn like rand() in PHP to pick an random number each time, thin i will put this rand() function in a for loop and then an if statment after the function to check if the random number is less than or equle to 4 so my code will look like  for (int i =0 ; i < 8 ; i ++){ int rn, n ; n = rand(); if (n<= 4 )rn = n else {rand()} ........ I can do this only if there was a function that picks random number in javascript ]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/f30aed8d73254a87b5bebef1506cd309)


## License

    Copyright [Ahmed Elsharkawy]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.