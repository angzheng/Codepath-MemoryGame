# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Angelina Zheng**

Time spent: **3** hours spent in total

Link to project: https://innate-carnelian-titanosaurus.glitch.me/


## Required Functionality

The following **required** functionality is complete:

* [ Y ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ Y ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [  ] Game buttons each light up and play a sound when clicked. 
* [  ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ Y ] Buttons use a pitch (frequency) other than the ones in the tutorial
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
![](https://i.imgur.com/LMyeDxx.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.rapidtables.com/web/css/css-color.html


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The tutorial was straightforward and very well-structured, so the only challenge from the required game 
features was properly getting the buttons to light up. The colored buttons were not lighting up when playing the sequence nor when a 
button was clicked by the user. The issue did not appear to be in the logic of the game since the console revealed that the user was 
still able to guess, and all counters keeping track of progress were correctly updating. Due to the clean structure of the code, 
it was quick to identify that the problem originated in the rules for the buttons in the style.css file. 
The mistake was a missing comma between the selectors, and after fixing that mistake, the code worked completely. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
What are aspects to consider when choosing one programming language over another for web development? 
What are some useful tools that can be used to test web code? 
Due to the clean structure of the project code, it was easy to debug a problem I encountered
with my code from simply using the console. However, with larger applications it would be more difficult
to target specific sections of code when finding mistakes. 
One note included in the tutorial is that it is important to choose a web-safe font,
and it is good practice to have fallback fonts. 
What other web features are there to look out for when considering
if they are supported by all browsers and devices? 
Furthermore, how can APIs be used to work with third party data? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would create original, digital drawings 
and add them to every one of the four buttons to make the game more interesting. 
I could then use the “hidden" class to hide the image until the user clicks on the button. 
Currently, the four buttons in my project play the musical notes A, D, G, and E similar to the strings on a violin. 
I could instead find audio clips of excerpts from songs as the sound played from each button. 
Instead of using an index to access different frequencies in freqMap, 
the index would access different audio clips for each button. 





## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.