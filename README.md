# Computer Game Doodle Jump
The plot mirrors the popular mobile game Doodle Jump: Doodle jumps and aims to reach the highest point. The project was developed in Java, using the Swing Framework for graphics.

## Content
[Game features](#game-features)

[Context](#context)

[Team](#team)

[Images](#images)

[Backlog](#backlog)

[Used technologies](#used-technologies)

[How to run](#how-to-run)

## Game features
* The Doodle jumps from one platform to another platform.
* The Doodle is teleported to the other border of the screen when it reaches the opposite one.
* The main goal is to reach the highest point by jumping.
* Game saves user's best result.

## Context
The project was developed as a group CBL Game Development assignment for the Programming course (2IP90) at Eindhoven University of Technology.

## Team
* [Aleksandr Vardanian](https://github.com/alex8399)
* [Ivan Bondyrev](https://github.com/iyubondyrev)

## Images

![Images](/images/image01.png)

## Backlog

1. **Render the main screen with a play button.**

    After app staring, the main screen should show up with a play button and the initial picture.

2. **Render a screen with platforms and Doodle after the play button was pressed.**

    Enter the game and press the play button.

3. **Move the user's screen with jumps of Doodle and render new platforms.**

    While  jumping up, the camera will follow the user.

4. **Render a fall of Doodle if it has missed a platform.**

    Just miss one of the platforms and Doodle will fall.

5. **Show the user's score in the corner.**

    In the top corner the user's score should be indicated. Score of the user depends on the height which the Doodle achieves in the game.

6. **Show screen with the highest score.**

    After the end of the game screen should be rendered with the user’s score.

## Used technologies
* Java
* Swing
* Gradle

## How to run

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/alex8399/doodle-jump.git
cd doodle-jump
```

2. **Build**
```bash
#For MacOs (sudo may be required):
zsh gradlew runGame  

#For Linux (sudo may be required):
bash gradlew runGame

#For Windows:
.\gradlew runGame
```

### How to play

Easy! Just use ```<-``` and ```->``` keys to move the doodle and jump as high as you can. Your score will be saved. You can use ```esc``` to return to the main menu.