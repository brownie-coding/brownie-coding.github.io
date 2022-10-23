	

# Brownie Coding

## Coding For Good (Badge 1)
<details><summary>Basics</summary>
   
Using Southeast Florida's Girl Scouts at Home Programs - Coding for Good Syllabus [pdf](https://www.gssef.org/content/dam/girlscouts-gssef/girl-experience/girl-scouts-at-home/flyers/Brownies%20-%20Coding%20Basics.pdf)
1.  Badge Part 1 - Create algorithms for a computer that follow a sequence
    *   [Loops & Events](https://studio.code.org/s/pre-express-2022)
    *   Complete Parts 1-3
2.  Badge Part 2 - Use Loops to improve your algorithm
    *   Complete Part 6 (same link as part 1)
3.  Badge Part 3 - Use events to make things happen
    *   Complete Part 11 (same link as part 1)
5.  Badge Part 4 - Learn about women in computer science
    *   [Grace Hopper -- Queen of Code](https://www.youtube.com/watch?v=5sNuPYJpSCI)
    *   [Grace Hooper Written Bio](https://www.womenshistory.org/education-resources/biographies/grace-hopper)
    *   [Ada Lovelace -- First Computer Programer](https://www.youtube.com/watch?v=2vg-0mlSnSE)
3.  Badge Part 5 - Create your own set of commands that use events
    *   [Dance Party](https://studio.code.org/s/dance-2019/lessons/1/levels/1)
</details>
<details><summary>Challenge (Coding with Scratch)</summary>

   # Challenge: Coding for Good with Scratch    
   Using the Brownies - Coding for Good Badge 1 [Grades: 2-3] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1s)
<details><summary>Introduction</summary>
   
   ## Creating a Gem Chaser Game

   Use your coding skills to create a game with 3 elements a cat, parrot and crystal. 

   The player will try to move the cat around the screen to avoid the bird while trying to catch the crystal.


   Steps for this game:
   The cat will be controlled by the player using the arrow buttons and look like it's walking.
   The crystal will move randomly around the board.
   The bird will chase the cat, and look like it's flying. 
   The cat will meow when it catches the crystal.
   The bird will make a different noise when it catches the cat.
</details>   
<details><summary>1. Setup</summary>
   
   ## Setup

   1.  Open the scratch website in a new tab - [Scratch](https://external.ink?to=/scratch.mit.edu)

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
     <p>After clicking on "Choose A Sprite" start typing in the search box to find both Parrot and Crystal.</p>
   <p><img src="/Crystal.png" width="300"></p>
   <p><img src="/Parrot.png" width="300"></p>
</details>
<details><summary>2. Code Sprite1</summary>   
   
   ##  Adding Code to Sprite1 [Video Help](https://www.youtube.com/watch?v=v2zEevGKPWs&t=388s)
   
   1. Adding Event Blocks (Yellow) to Sprite1 [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=432s)
        *  Click on the Correct Sprite - start with Sprite1 (the cat) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=387s)
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
</details>  
<details><summary>3. Test your code </summary>   

   ### Test your code       
   * Do you noticing that Sprite1 moves off the end of the screen [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=827s)
       * Keep Sprite1 in the frame by adding the Motion Block "If on edge, bounce" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=848s)
       <img src="/Sprite1_bounce%20on%20edge.png" width="400">
   * Do you want Sprite1 to look like it's walking or running? [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=848s)
       * Add the Looks Block "next costume". [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1040s)
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to move faster or slower? 
       * Change the number in the "Move __ Steps" block.  [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1100s)
       * Increase to move faster, recommend changing to 20.
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to be larger or smaller, Crystal to be smaller of large?
       * Change the size in the setup area. [Video Sprite](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1135s) [Video Crystal](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1180s)
</details>
<details><summary>4. Code the Crystal </summary>    
   
   ## Adding Code to Crystal     
Now that the Cat can walk around we'd like the crystal to move around the board.

We would like this event to start as soon as we click the green flag. 
1. Click on the Crystal Sprite
2. Adjust the size of the Crystal
3. Add an Event Block 
  * Add the Events Block "when green flag clicked" to the design space. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1199s)
4. Add a Movement Block
  * Add the Movement Block "glide one secs to random position" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1216s)
5. Add a Loop using a Control Block
  * We want the Movement Block to happen again and again while the game is going, if you test it now it does not [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1225s)
  * A Loop is ideal for this. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1290s)
  * Add a "forever" block (orange) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1363s) under the Event Block (yellow) then put the Movement block (blue) in the grove [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1376s)
<img src="/Crystal_loop.png" width="400">
</details>
<details><summary>5. Code the Parrot </summary>    
   
   ## Adding Code to Parrot
   Now the movement for the Sprite1 and Crystal are set, we'd like the bird to chase the Sprite1.
1. Click on the Parrot Sprite [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1465s)
2. Adjust the size of the Parrot 
3. Add an Event Block 
   * Add the Events Block "when green flag clicked" to the design space. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1495s)
4. Add a Movement Block to Change direction pointing
   * Add the Movement Block "point towards _____" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1500s)
   * Select Sprite1 from block menu
5. Add a Movement Block to take steps  
   * Add the Movement Block "move __ steps"
   * The number chosen should be smaller than the number of steps Sprite1 takes. This number can be adjusted to make the game easier or harder. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1625s)
6. Add a Loop using a Control Block
   * We want the Movement Block to happen again and again while the game is going, so we are adding a loop again.
   * Add a "forever" block (orange) under the Event Block (yellow) then put the Movement blocks (blue) in the grove
<img src="/Parrot_move.png" width="400">
</details>
<details><summary>6. Make the Parrot look like it's flying </summary>    
   
   ### Making the Parrot look like it's flying
1. Add an Events Block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1780s)
   * Add the Events Block "when green flag clicked" to the design space.
2. Add a Looks Block
   * Add a Looks Block "next costume"
3. Add a Loop using a Control Block
   * We want the Movement Block to happen again and again while the game is going, so we are adding a loop again.
   * Add a "forever" block (orange) under the Event Block (yellow) then put the Looks Block (purple) in the grove
   * If you try the code now, the costume will change too quickly
4. Add a Contol Block
   * Add Controls Block "wait 1 sec" into the loop
   * Adjust the number to control the speed.
<img src="/Parrot_loops.png" width="400">
</details>
<details><summary>7. Add a sound to Sprite1 </summary>    
   
   ### Making the Sprite1 make a sound when it catches Crystal
1. Add an Events Block (yellow) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1998s)
   * Add the Events Block "when green flag clicked" to the design space.
2. Add a Controls Block (orange)
   * Add an "If <> Then" Block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2029s)
3. Add a Sensing Block (Teal)
   * Add "touching ____ " Block into the "If Then" Block. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2060s)
   * Select Crystal from the menu 
4. Add a Sounds Block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2118s)
   * Add a "play sound Meow until done"
5. Add a Loop using a Control Block
   * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2155s)
   * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove.
<img src="/Noise_Sprite1_crystal.png" width="400">
</details>
<details><summary>8. Add sound to Parrot </summary> 
   
   ### Making the Parrot make a sound when it catches Sprite1
1. Add an Events Block (yellow) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2260s)
     * Add the Events Block "when green flag clicked" to the design space.
2. Add a Controls Block (orange)
     * Add an "If <> Then" Block
3. Add a Sensing Block (Teal)
     * Add "touching ____ " Block into the "If Then" Block.
     * Select Sprite1 from the menu 
4. Add a Sounds Block
     * Use the sounds tab to add a new sound. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2117s) 
     * Add a "play sound Meow until done"
     * Change "Meow" to the new sound.
5. Add a Loop using a Control Block
     * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop again.
     * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove
   <img src="/Noise_Parrot_Sprite1.png" width="400">
</details>
   
### Trouble Shooting
Try playing your game. Can you change parameters to make it easier or harder? What do you think needs to change? Can you change it?

Don't forget to save your game!
   
Let others play your game!
</details>

## References:
*   https://code.org/dance
*   Southeast Florida's Girl Scouts at Home Programs - Coding for Good Syllabus [pdf](https://www.gssef.org/content/dam/girlscouts-gssef/girl-experience/girl-scouts-at-home/flyers/Brownies%20-%20Coding%20Basics.pdf)
*   Coding for Good Badge 1 [Grades: 2-3] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1s)
