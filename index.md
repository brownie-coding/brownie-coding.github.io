# Brownie Coding

## Coding For Good
1.  Badge Part 1 - Create algorithms for a computer that follow a sequence
    *   [Loops & Events](https://studio.code.org/s/pre-express-2022)
    *   Complete Parts 1-3
2.  Badge Part 2 - Use Loops to improve your algorithm
    *   Complete Part 6 (same link as part 1)
3.  Badge Part 3 - Use events to make things happen
    *   Complete Part 11 (same link as part 1)
5.  Badge Part 4 - Learn about women in computer science
    *   [Grace Hopper -- Queen of Code](https://www.youtube.com/watch?v=5sNuPYJpSCI)
    *   [Ada Lovelace -- First Computer Programer](https://www.youtube.com/watch?v=2vg-0mlSnSE)
3.  Badge Part 5 - Create your own set of commands that use events
    *   [Dance Party](https://studio.code.org/s/dance-2019/lessons/1/levels/1)
      
# Challenge Coding for Good with Scratch 
## Creating a Gem Chaser Game
Use your coding skills to create a game with 3 elements a cat, parrot and crystal. 

The cat will be controlled by the arrow buttons and the player will try to move the cat around the screen to avoid the bird while trying to catch the crystal. The cat will meow when it catches the crystal.

The bird will chase the cat, and make a noise when it catches the cat.

The crystal will move randomly around the board.

## Setup
1.  Go to the scratch website - [Scratch](https://scratch.mit.edu)
1.  If you would like to Login ask an adult to help you set up an account, or you can just use the browser version you can save it to the computer without creating an account. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=270s)
2.  Then click "Create" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=260s)
![Click Create](/CreateButton.png)
4.  Name your program if you signed in. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=265s)
5.  Pick a Backdrop [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=276s)
     * Any backdrop will work, pick your favorite
     <img src="/ChooseABackground.png" width="300">

6.  Pick the 3 Sprites 
     
     * Sprite1 (the cat is already picked for you)
     * Add Crystal, and Parrot
     <img src="/ChooseASprite.png" width="300">
    
     After clicking on "Choose A Sprite" start typing in the search box to find both Parrot and Crystal.
     <img src="/Crystal.png" width="300"> 
     
     <img src="/Parrot.png" width="300">

##  Adding Code to Sprite1 [Video Help](https://www.youtube.com/watch?v=v2zEevGKPWs&t=388s)
 1. Adding Event Blocks (Yellow) to Sprite1 [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=432s)
       *  Click on the Correct Sprite - start with Sprite1 (the cat) [Video Help](https://www.youtube.com/watch?v=v2zEevGKPWs&t=387s)
       *  Add the Event Block - "when ___ key pressed"
       *  Change the key so each Event responds to a different key
       *    <img src="/SpriteEventBlocksPickkey.png" width="300">
       *  One event for each arrow key up, right, left and down
       *    <img src="/Sprite1_eventblocks.png" width="300">
  2. Adding Motion Blocks (Blue) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=540s)
    
    
     A.   Change the direction the sprite points by adding the Motion Block "point in direction __ " [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=592s) 
       *   Add the movement block to each event - 4 total, 
       *   Adjust the direction to face direction of movement [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=615s)
     
     B.    Take Steps by adding "Move __ Steps" block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=636s)
       *   Check that the 4 events (yellow blocks) have 2 motion blocks (blue) under each them 
       *   <img src="/Sprite1_steps%20and%20direction.png" width="400">
       *   That the arrow key matches the direction of the steps [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=660s)
       
### Test your code       
   * Do you noticing that Sprite1 moves off the end of the screen [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=827s)
       * Keep Sprite1 in the frame by adding the Motion Block "If on edge, bounce" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=848s)
       <img src="/Sprite1_bounce%20on%20edge.png" width="400">
   * Do you want Sprite1 to look like it's walking or running?
       * Add the Looks Block "next costume".
   * Do you want Sprite1 to move faster or slower?
       * Change the number in the "Move __ Steps" block.  
   * Do you want Sprite1 to be larger or smaller?
       * Change the size in the setup area.
       
## Adding Code to Crystal     
Now that the Cat can walk around we'd like the crystal to move around the board.

We would like this event to start as soon as we click the green flag. 
1. Click on the Crystal Sprite
2. Adjust the size of the Crystal
3. Add an Event Block 
  * Add the Events Block "when green flag clicked" to the design space.
4. Add a Movement Block
  * Add the Movement Block "glide one secs to random position"
5. Add a Loop using a Control Block
  * We want the Movement Block to happen again and again while the game is going, so we are adding a loop.
  * Add a "forever" block (orange) under the Event Block (yellow) then put the Movement block (blue) in the grove


## Adding Code to Parrot
Now the movement for the Sprite1 and Crystal are set, we'd like the bird to chase the Sprite1.
1. Click on the Parrot Sprite
2. Adjust the size of the Parrot

4. Add a Movement Block to Change direction pointing
  * Add the Movement Block "point towards _____"
  * Select Sprite1 from block menu
4. Add a Movement Block to take steps  
  * Add the Movement Block "move __ steps"
  * The number chosen should be smaller than the number of steps Sprite1 takes. This number can be adjusted to make the game easier or harder.
5. Add a Loop using a Control Block
  * We want the Movement Block to happen again and again while the game is going, so we are adding a loop again.
  * Add a "forever" block (orange) under the Event Block (yellow) then put the Movement blocks (blue) in the grove

### Making the Parrot look like he's flying
3. Add an Events Block 
  * Add the Events Block "when green flag clicked" to the design space.
4. Add a Looks Block
  * Add a Looks Block "next costume"
5. Add a Loop using a Control Block
  * We want the Movement Block to happen again and again while the game is going, so we are adding a loop again.
  * Add a "forever" block (orange) under the Event Block (yellow) then put the Movement blocks (blue) in the grove
  * If you try the code now, the costume will change too quickly
5. Add a Contol Block
  * Add Controls Block "wait 1 sec" into the loop

### Making the Sprite1 make a sound when it catches Crystal
3. Add an Events Block (yellow)
  * Add the Events Block "when green flag clicked" to the design space.
4. Add a Controls Block (orange)
  * Add an "If <> Then" Block
5. Add a Sensing Block (Teal)
  * Add "touching ____ " Block into the "If Then" Block.
  * Select Crystal from the menu 
6. Add a Sounds Block
  * Add a "play sound Meow until done"
8. Add a Loop using a Control Block
  * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop.
  * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove.

### Making the Parrot make a sound when it catches Sprite1
3. Add an Events Block (yellow)
  * Add the Events Block "when green flag clicked" to the design space.
4. Add a Controls Block (orange)
  * Add an "If <> Then" Block
5. Add a Sensing Block (Teal)
  * Add "touching ____ " Block into the "If Then" Block.
  * Select Sprite1 from the menu 
6. Add a Sounds Block
  * Use the sounds tab to add a new sound.
  * Add a "play sound Meow until done"
  * Change "Meow" to the new sound.
8. Add a Loop using a Control Block
  * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop again.
  * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove

### Trouble Shooting
Try playing your game. Can you change parameters to make it easier or harder? What do you think needs to change? Can you change it?

Let others play your game!

## References:
*   https://code.org/dance
