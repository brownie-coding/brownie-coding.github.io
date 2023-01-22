	

# Brownie Coding
<details><summary>Badge 1</summary>
	
[Badge 1](../badge1.md)
</details>
<details><summary>Badge 2</summary>
	
# Digital Game Design
<details><summary>Planning and Design</summary>
   
   Program a maze game. 

   The player will try to navigate the maze using the Sprite (Cat) to the end point. [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=122s)
	
   Steps to create this game:
   1. Open Scratch
	
   2. Develop a maze background
	
   3. Deside how the Sprite will be controlled by the player (example is arrow buttons)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=335s)
	
   4. The cat will should bounce off boundaries and maze walls.
	
   5. The cat will meow, and change background, and size when reaches the end of the maze.
	
   6. The cat and background will reset when the game is restarted.
	
Example from Brownies - Coding for Good Badge 2 [Grades: 2-3] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1s)
	
</details>
<details><summary>Game Design (Coding with Scratch)</summary>

   ## Digital Game Design with Scratch    
 
<details><summary>1. Setup</summary>
   
   ## Setup

   1.  Open the scratch website in a new tab - <a href="http://scratch.mit.edu" target="_blank" rel="noopener">Scratch</a>

   2.  If you would like to Login ask an adult to help you set up an account, or you can just use the browser version you can save it to the computer without creating an account. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=270s)

   3.  Then click "Create" [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=260s)
![Click Create](/CreateButton.png)

   4.  Name your program if you signed in. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=265s)

   5.  Pick a Sprite 
     * Sprite1 (the cat is already picked for you - but you can pick a different one)
	
   6.  Draw your Backdrop [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=318s) or  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=420s)
	This will be your maze. You can start simple then make it more complex after you get the rest of your program working.

</details>
<details><summary>2. Draw your Maze</summary> 
   1. Draw out a simple maze on paper with a circle for start and a different circle for end point [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=420s)
   
   2. Click on "Stage"  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=442s)
   
   3. Click "Backdrop" tab - this will allow you to draw on your backdrop.  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=473s)
   <img src="/BackdropDesign.png" width="400">
   
   4. Pick a color for your maze walls, the example is purple, but you can use any color. It is important to make all of the maze walls in the same color. Pick the red diagonal line in the outline box - this will make the rectangles used for the walls one color and easier to program.  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=485s)
  <img src="/ColorSetup.png" width="400">
   
   5. Make sure to have a large enough maze path so your sprite can move through it. You can make your Sprite smaller (see step 5)!
  
   6. Add shape in different colors for the start and end. The example uses a green circle for the start, and a red circle for the end.  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=654s)
   <img src="/MazeExample.png" width="400">

</details>
<details><summary>3. Code Sprite1</summary>   
   
   ##  Adding Code to Sprite1 [Video Help](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=874s)
   
   1. Adding Event Blocks (Yellow) to Sprite1  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=897s)
        *  Click on the Sprite - (the cat)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=874s)
        *  Add the Event Block - "when ___ key pressed" 
        *  Change the key so each Event responds to a different key
        *    <img src="/SpriteEventBlocksPickkey.png" width="300">
        *  One event for each arrow key up, right, left and down
        *    <img src="/Sprite1_eventblocks.png" width="300">
   2. Adding Motion Blocks (Blue)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=960s)
    
       A.   Change the direction the sprite points by adding the Motion Block "point in direction __ "  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1033s) 
       *   Add the movement block to each event - 4 total, 
       *   Adjust the direction to face direction of movement
     
       B.    Take Steps by adding "Move __ Steps" block  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1043s)
       *   Check that the 4 events (yellow blocks) have 2 motion blocks (blue) under each them 
       *   <img src="/Sprite1_steps%20and%20direction.png" width="400">
       *   That the arrow key matches the direction of the steps  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1145s)
</details>  
<details><summary>4. Test your code </summary>   

   ### Test your code       
   * Do you noticing that Sprite1 moves off the end of the screen [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=827s)
       * Keep Sprite1 in the frame by adding the Motion Block "If on edge, bounce"  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1400s)
       <img src="/Sprite1_bounce%20on%20edge.png" width="400">
   * Do you want Sprite1 to look like it's walking or running? [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=848s)
       * Add the Looks Block "next costume". [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1040s)
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to move faster or slower? 
       * Change the number in the "Move __ Steps" block.  [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1100s)
       * Increase to move faster?, recommend changing to 20.
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to be larger or smaller, to be smaller or larger?
       * Change the size in the setup area.  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1490s)
</details>  
	
<details><summary>5. Start the Game when the flag is pressed </summary> 
   
   ### Sprite1 starts at the Start (green circle)
1. Add an Events Block (yellow)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1450s)
   * Add the Events Block "when green flag clicked" to the design space. 
2. Set the Sprite's size to fit into your maze.   
    * Use a Looks Block (purple)
    * Add "set size to ___ %" under the yellow Control block "when green flag clicked" (example is 25%) [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1490s)
3. Set the Sprite's location to the green circle  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1560s)
    * Move the Sprite using your mouse to the starting location - this should change the x and y position numbers. 
    * Use a Motion Block (blue)
    * Add the "go to x:__ y:__" under the yellow Control block "when green flag clicked" (example coordinates are (x: 196, y: -122)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1640s)
4. Reset the background
    * Use a Looks Block (purple)  
    * Add the "switch backdrop to ____" block under the yellow Control block "when green flag clicked"  
    * Set block to "backdrop1"	
   <img src="/MazeSetup.png" width="400">
</details>
	
<details><summary>6. Bounce off the Maze! </summary>   

2. Add a Controls Block (orange)
   * Add an "If <> Then" Block
3. Add a Sensing Block (Teal)
   * Add "touching color ____ " Block into the "If Then" Block.
   * Use the selector button and pick the maze color (purple)  [Video](https://www.youtube.com/watch?v=JpbUGa6yE9U&t=1725s)
4. Add a Motion Block (blue)
   * Add a "move __ steps" block
   * Add a - sign infront of the number of steps your Sprite moves in response to an arrow key
5. Add a Loop using a Control Block
   * We want the Sprite to bounce off the maze again and again while the game is going, so we are adding a forever loop.
   * Add a "forever" block (orange) under the Event Block (yellow) then put the if statement in the grove
   <img src="/MazeStart.png" width="400">
</details>

<details><summary>7. Add a suprise background </summary>    
   
   ### Making the Sprite1 make a sound and enter a new background when gets to the end of the maze
1. Add an Events Block (yellow) [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1998s)
   * Add the Events Block "when green flag clicked" to the design space.
2. Add a Controls Block (orange)
   * Add an "If <> Then" Block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2029s)
3. Add a Sensing Block (Teal)
   * Add "touching color ____ ?" Block into the "If Then" Block. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2060s)
   * Use the sampling tool to pick the color of the end shape (red) 
4. Add a Looks Block (purple)
   * switch backdrop to your favorite one (Example is Space City 2)	
5. Add a Sounds Block [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2118s)
   * Add a "play sound (Meow) until done"
6. Add a Looks Block (purlple)
   * Add "set size to ___%"
   * Pick a new size (example uses 150)
5. Add a Loop using a Control Block
   * We this to be tested over again while the game is running, so we are adding a forever loop. [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=2155s)
   * Add a "forever" block (orange) under the Event Block (yellow) then put the If block and all other blocks (purple) in the grove.
<img src="/MazeEnd.png" width="400">
</details>

   

   
### Trouble Shooting
Try playing your game. Can you change parameters to make it easier or harder? What do you think needs to change? Can you change it?

Don't forget to save your game!
   
Let others play your game!
</details>	
</details>
</details>

## References:
*   https://code.org/dance
*   Southeast Florida's Girl Scouts at Home Programs - Coding for Good Syllabus [pdf](https://www.gssef.org/content/dam/girlscouts-gssef/girl-experience/girl-scouts-at-home/flyers/Brownies%20-%20Coding%20Basics.pdf)
*   Coding for Good Badge 1 [Grades: 2-3] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=v2zEevGKPWs&t=1s)
