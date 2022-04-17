# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Raul Chakraborty**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/iodized-silky-citrus?path=script.js%3A13%3A17

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
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] List anything else that you can get done to improve the app!
- [X] Different game modes
- [X] Scoreboar with current score and highest score
- [X] A visual timer

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
- The game goes faster as you progress
![](https://i.imgur.com/7lB8Zd5.gif)
- The game ends if you are not fast enough
![](https://i.imgur.com/V437rHe.gif)
- The hard mode is amode that keepsgoing until you lose and keeps track of the highest score
![](https://i.imgur.com/c6t8XYa.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
- https://stackoverflow.com/questions/3842614/how-do-i-call-a-javascript-function-on-page-load#:~:text=You%20have%20to%20call%20the,load%20event%20of%20the%20document.
- https://www.taniarascia.com/how-to-use-local-storage-with-javascript/
- https://code-boxx.com/display-dynamic-content-html/
- https://stackoverflow.com/questions/40638402/why-wont-my-countdown-timer-start-and-stop


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge I faced was implimenting the timed feature, where the user loses if they do not answer in time. I did not know where to start and how to even implement something that countdowns in real time. So I did what I do best, which is google. I searched a lot of different terms on google until I found someone on stackoverflow who created a sort of countdown timer, something similar to what I needed. So i looked at the solution, copied it down, then I started making tweaks to it so it would fit my senario better. It took a lot of iterations and testing before I came to the final product. Although there is a bug I could not fix, which is if you stop the game before the timer can start, even after the game ends the time will keep running and make you lose the game, I struggled with this a lot and it would take me longer than the 5 hour limit to work and fix it.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[As a Junior Web Developer for my university, I have touched on a lot of web development topics, but the one area I struggle the most with when it comes to styling and creating styles that are responsive and how to use JS to do animations and designs that include paralax. Using JS to style and annimate is a cool topic and I would love to learn more about that.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours, I would work on cleaning up and writing better JS, and I would also attempt to fix the bug that I mentioned in number 2. I would also add better stlying and more features like keeping track of how many times you won or lost and add new game modes.]



## Interview Recording URL Link

[My 5-minute Interview Recording](
https://syracuseuniversity.zoom.us/rec/play/_0c9HSWwdW-qjFB0NI6CbMPPKW-vfIkBOmnr0XZns3AXX2bhEih5vNdrlHNSqbacPm2hFrAbzlclqWyh.0HD0h2wutytSwf91?continueMode=true
)


## License

    Copyright [Raul Chakraborty]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
