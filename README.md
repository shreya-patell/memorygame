# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Shreya

Time spent: 2.5 hours spent in total

Link to project: https://glitch.com/edit/#!/fluff-fifth-cylinder

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/c1gNqzF.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

w3schools.com (HEX code for colors and CSS properties )

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Despite following the instructions, I wasn't seeing the same results. My startGame function wasn't functioning the same as described. Also, when trying to console output the code, it took me a while to find the output and see the messages. For both issues, I re-read the instructions the twice to see where I was going wrong. With the startGame function, after looking at it twice, I realized I was missing the "remove" for "stopBtn". For the console output, it took a quick google search to access to figure out that what I was clicking was wrong and eventually figured out the correct way. Since the instructions were detailed and easy to understand, there weren't any significant difficulties that I faced. A lot of minor difficulties were resolved by re-reading the instructions or doing a quick google search.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Web developement specifically front-end development is something that intrests me and something I want to explore more of. What are the best tools for web development? What makes a successful website? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours, I would definitely want to design it a lot different, in terms of layout, colors, and overall styling. I would love to add additional features like adding a ticking clock and giving the player 3 strikes. 


## License

    Copyright [Shreya Patel]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
