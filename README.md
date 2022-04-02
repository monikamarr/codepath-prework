# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Monika Marek

Time spent: 8 hours spent in total

Link to project: https://glitch.com/edit/#!/memory-tweak-game

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] the game elements are centered on the website

## Video Walkthrough (GIF)

![x](https://i.imgur.com/oTvfvl4.gif)
![x](https://i.imgur.com/Ot56da3.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- https://www.w3schools.com/css/css_align.asp
- https://www.w3schools.com/css/css_float.asp
- https://www.techotopia.com/index.php/JavaScript_Variable_Types
- https://www.w3schools.com/css//css_font_websafe.asp
- https://www.w3schools.com/css/css3_images.asp
- https://www.w3schools.com/howto/howto_css_images_side_by_side.asp
- https://www.w3schools.com/html/html_paragraphs.asp
- https://www.w3schools.com/css/css_margin.asp
- https://www.w3schools.com/cssref/pr_class_display.asp
- w3schools.com/css/css_inline-block.asp
- https://colorhunt.co/palettes/night
- https://stackoverflow.com/questions/2813653/can-an-element-have-both-an-id-and-a-class
- https://www.tutorialspoint.com/css/css_positioning.htm
- https://unicode-table.com/en/2606/
- https://www.tutorialspoint.com/How-to-set-Heading-alignment-in-HTML#:~:text=To%20set%20the%20heading%20alignment,the%20CSS%20property%20text%2Dalign.
- https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   For me, the most challenging part of the Light and Sound Memory Game project was to figure out how to align the game buttons so that
   they stay in the middle of the webpage. I tried to center them by using different position properties, float properties, display
   properties, and text-align properties. None of the properties would help me obtain the desired output. I used the “Inspect” tool to try
   to tackle this problem in real-time. The buttons would get centered but they would align in a vertical position, one under another
   instead next to each other. I also read multiple articles (mostly from www.w3schools.com – all sources are attached in the readme.md file)
   on how to fix it. I tried to treat the game buttons as if they were images. That also did not help with the alignment. I was not able
   to adjust the buttons by using the mentioned css properties. Therefore, I decided to manually adjust the buttons so that they appear
   in the middle of the page. I increased the left- and right-margins for each game button to get the effect of them being centered.
   I realize I am missing a small puzzle. I believe this has something to do with the <div> being a parent for the buttons. I tried the
   different properties on the <div>’s ID and also the buttons’ ID’s to see the behavior of the inheritance. Unfortunately none would
   give the wished result.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   How to align the buttons in the middle of <div>?

- Do developers run into similar problems to mine? Is it common to have issues with element positioning on the webpage?
- Are there any other ways to fix that problem?
- Was my project part of full-stack web development? – Is the JavaScript part of the back-end?
- How to create a mobile version of the project written in glitch?
- What frameworks/ languages could improve my project?
- Is it better to work in an online IDE or a desktop editor? Which one is most recommended for web development?
- What percentage of a web designer’s job is to actually write code? – I have noticed that planning and researching through the documentation took me the majority of the time (besides getting stuck at CSS positioning).

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   If I had more time to work on the project, I would work out how to align the buttons in the middle of the div. I would also add more
   features into the project. For example, I would read on how to add a timer, so that the player would have to make a decision under
   pressure. This would add another level of difficulty to the game. Maybe a point scoring system so that it is more rewarding and
   competitive for the player.
   I would also like to add more buttons when the client reaches a certain level – for example, when the person playing wins three
   times in a row, a new button appears each time. The game would be over after 10 rounds and the client would be able to see the
   points won. There would be 1 point for winning one round, 5 points for hitting the next level.
   I want to figure out how to add different tones for the buttons. At higher difficulties, the game would add random picks for the game
   pattern.

## Interview Recording URL Link

https://www.loom.com/share/d326171522a44128aa88c9f81c757a33

## License

    Copyright [Monika Marek]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
