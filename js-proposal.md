# Pac-Man - A recreation of a timeless classic

### Why I want to build Pac-Man for my Javascript Project

I wanted to build a game, and I love the nostalgia and relatability of Pac-Man. I am looking forward to tackling these nuances and complexities:
- Creating ghost AIs. All four ghosts will need to maintain similar navigation logic but also need to move independently of each other.
- Adding sound effects to key events.
- Overall polish of the gameplay and navigation need to be spot-on, in order to evoke nostalgia.

### Background and Overview
Pac-Man is a classic arcade game from the 1980s. The player navigates Pac-Man through a maze to collect dots while avoiding colorful ghosts (Blinky, Pinky, Inky and Clyde). The player wins a level if they successfully collect all the dots.
There are special dots called "power pellets" that give Pac-Man the temporary ability to eat the ghosts.

### Functionality & MVP
In this rendition of Pac-Man:
- [X] Player will be able navigate Pac-Man through the maze.
- [X] Four AI ghosts will chase Pac-Man. Player will lose a life if a ghost catches Pac-Man.
- [X] Player can eat a power pellet to turn the ghosts blue, and can earn points by having Pac-Man eat the ghosts when they are blue.
- [X] Player will have multiple lives to beat Pac-Man
- [X] There will be sound effects for general navigation, when Pac-Man is eaten, and when the ghosts are eaten.

In addition, the following aesthetics and styling will be applied:
- [X] A scoreboard on the right
- [ ] An instructional about how to navigate and play Pac-Man.
- [ ] Gameover/won  display when game ends

### Wireframes
![](https://github.com/youknowhu/Pac-Man/blob/master/prep/pacman.png)


### Architecture and Technologies
This project will be implemented with the following technologies:
* Vanilla JavaScript for overall structure and game logic.
* Webpack to bundle and serve up the various scripts.

Pac-Man will be comprised of the following files.
* `board.js:` this script will handle the logic for creating the Pac-Man maze and maintaining DOM elements.
* `pacman.js:` Pac-Man's navigation and abilities.
* `ghost.js` Ghost AI logic and navigation.
* `audio.js` Manages sound effects of the game.
* `game.js` Manages overall gameplay (lives, score, running the game, etc.)

### Implementation Timeline

**Over the weekend:** Planning and general layout
- [X] Complete Breakout Tutorial using vanilla Javascript, for general foundation on how to create a game with Javscript
- [X] Finish Maze layout with Pac-Man and ghost images

**Day 1:** Complete Pac-Man and ghost navigation
- [X] Complete Pac-Man navigation/movement throughout maze (can't move through walls, Pacman mouth direction is pointed in direction of navigation)
- [X] Single ghost navigation and logic (normal mode, not blue)

**Day 2:** Add additional ghosts and incorporate power pellets
- [X] Multi ghost navigation
- [X] Add Power Pellets:
    - [X] Turns ghosts blue temporarily
    - [X] Pac-man can eat the ghosts
    - [X] Ghosts move away from Pac-Man

**Day 3:** Add scoring, lives, and sound effects
- [X] Add scoring logic and display
- [X] Add multi-lives
- [X] Add music sound effects

**Day 4:** Potential Bonus Features
- [X] Add scoreboard?
- [ ] Start game, pause, game over

**Day 5:** Polish
- [ ] Polish, instructionals, styling

### Bonus features
- [ ] Splash with introduction to the ghosts/how scoring will work
- [ ] Highest scores scoreboard
- [ ] Multiple maze levels
