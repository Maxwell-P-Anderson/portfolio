---
layout: default
title: “Button Bop!”
---

# "[Button Bop](#button-bop)!"

# Project Background

 In my freshman year of college, I took a generaly engineering projects class. This class aimed to give students with no experience with any hands on projects the relevant skills to take a projct from start to finish. This included classes and workshops that aimed to teach the basics of Arduino, machining and 3d modeling.
 
With my experience from my high school's robotics class and the "Pneumatic wings" project, I was already ahead of the curve in this knowledge base, with a few years of solidworks under my belt, and training on most of the basic machining processes.

Our final project for this class was given to us by a local elementary school with a program that specially helped kids with autism, and other disabilities. The teachers of this program wished to have a game that would encourge their students to develop their hand eye cordination, as that is often a difficulty for students with these disabilities. Working closely with our client, our team came up with a concept for a game involving big buttons and colorful RGB LED's we titled "Button Bop!"

The goal of the game was to make a game that was both visually and physically engaging to the students with a scoring system to allow teachers to track student progress. We did this by having our board contain a central LCD display that displayed a desired color, with six acryllic plates that would glow a random color. The player would then press the button next to the plate that matched the LCD. 

Here is a video of the game operating and being played:

<iframe width="560" height="315" src="https://www.youtube.com/embed/qsCmzDEvox4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Difficulties

Before this project, I knew next to nothing about Aurduino programming, and niether did my team mates. Unfortunately for our team our game would have to implement an aurduino in order to run the game logic, and coordinate the different LED circuits. I decided to step up and learn everything we needed to know to develop this game and became our team's resident programmer. I spent 8 hours a week for 6 weeks in the office hours of the projects consulting engineer who taught the aurdino workshops in order to develop my own skills and develop the logic of our game. It would have been more simple to have set positions for each LED color on the board, but we wanted to randomize the position of the colors each round. This was to better stimulate the students and make it so they had to process more information to excecute the each action.

Another difficulty, was that there where more than a few conflicts between some members of our team. One team member would often disregard the only woman on our team, and critizise her ideas disproportionately to how he would criticize the rest of the team. This lead to our team mate feeling increasesingly frustrated and isolated. Myself and another team member of ours consistently stood up for her, but it lead to an environmental that was antithetical to cooperation. There where other issues around team memnbers fooling around and nt working productively. I learned a lot about conflict resolution, such as how tocome to comprimises on design choices when needed and drawing hard lines between acceptable and unacceptable behavoir when necessary.

# Lessons Learned

I had some prior experience working with clients and project goals, but this was my first opportunity and deepen these skills and apply them to a long-term project. I learned how to ask the right questions to get to the heart of what our client wanted out of this project. Translating vague ideas into actionable engineering specifications is a hard skill to learn but this project was simple and had a clear direction, which provided a great opportunity to learn.

I also learned the value of incremental progress in prototypes and testing individual components of a project in development. As the point person for the code and electrical circuitry, the way I learned how to put everything together was to do it piece by piece. First I set up the LED circuits, making sure I could address individual pins, and control their brightness with different resistors. Next, I worked on activating the LEDs with a button. Then I worked on toggling the button, then finally debouncing it. Once I fundamentally understood those circuits and programs, I worked on making an RGB LED that would turn on a random color in a loop. I predetermined four colors to switch between and created an array that would randomly feel a value into a switch statement to turn on the LED. Once that was finished, I created a similar array of buttons corresponding to each color. 

This was the first working version of our game. The LED would light up a color (Red, Green, Blue, Yellow) and the user would press the corresponding button. If the colors matched, then they got a point, if it didn't the user got no points and the next round started. Each button press caused the system to tick forward and choose a new random color. The feeling of creating and the actual working game was tremendous. Four weeks of hard work and studying paid off and when I got to show our progress to our client and they loved it! 

Here is that video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/VwK3r0ILzV8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Finally, our class also required us to perform some "Market Research" by showing a prototype of our project to members of our target audience, and garnering feedback. Over the fall break I went back home and took the prototype shown above to my younger brother, and a few of the kids in the neighborhood. I explained to them the project, showed them drawings of what our final product would look like, and asked them to play the game. They all really enjoyed the concept of the game and their feedback was suprisingly insightful! This feedback and the videos I took of their reactions went into our groups PDR presentation to explain changes in our final design.

Here are photos of them playing our game:

### Hoshea - Neighbor
<img src="../images/JPEGs/HosheaTesting.png" width="300">

### Mikayah - Neighbor
<img src="../images/JPEGs/MikayahTesting.png" width="300">

### Ovadiyah - Neighbor
<img src="../images/JPEGs/OvadiyahTesting.png" width="300">

### Miles - Younger Brother
<img src="../images/JPEGs/MilesTesting.png" width="300">

## Technical Skills

* Programming in C++
* Arduino programming
* Soldering
* Electrical circuts
* Game development

## Soft Skills

* Client communication
* Team communication
* Conflict resoluition
