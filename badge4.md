[Home](/)

# Junior Badge 1 - Coding For Good

<details><summary>Pong</summary>

   
   <details><summary>What is Pong?</summary>     
   Pong is a game where you use a paddle to hit a moving ball to defend a space or edge 
   
      <img src="/Pong.png" width="300">
   
   For this part of the badge you will use Scratch to program your own Pong game.

   In this game you are going to program: 
   
     * A ball to move around your space. 
     * A paddle that you can control with arrow keys.
     * An area to defend.
     * Add different sounds when the paddle hits the ball and when the ball hits the area/item you are defending.
 
   Watch the game in action: [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=120s)
</details>
<details><summary>Coding your Pong Game</summary>   
<details><summary>1. Setup</summary>

   1.  Open the scratch website in a new tab - <a href="http://scratch.mit.edu" target="_blank" rel="noopener">Scratch</a>

   2.  If you would like to Login ask an adult to help you set up an account, or you can just use the browser version you can save it to the computer without creating an account.
     
   3.  Then click "Create" Button at the top of your screen.

       <img src="/CreateButton.png" width=500>

   4.  Name your program if you signed in. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=120s)

   5.  Pick a Backdrop from the bottom right corner [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=208s)
        * Any backdrop will work, pick your favorite - you can go back and change this later
        * Search tool will let you choose from the available backgrounds  
       <img src="/ChooseABackground.png" width="300">

   6.  Pick a Sprite for your Ball

       Clicking on "Choose A Sprite" start typing in the search box to find either a Ball or your own shape.</p> 
        * Add Ball  (or your own choice)
        * Sprite1 (the cat is already picked for you)
        * You can delete this one unless you want to use the cat.
            * Delete it by clicking on the Sprite1, and then the blue trash can on the Sprite1 image.

        <img src="/ChooseASprite.png" width="300">
     
   8. Pick a Paddle Sprite
     <p>After clicking on "Choose A Sprite" start typing in the search box to find either a Paddle or your own shape.</p>

   9. Create a zone to defend
       * Click on white rectangle in bottom righthand corner that says "Stage"
       * Then click on the Backdrops Tab
       *  <img src="/Backdrops.png" width="300">
       * Select Square paint tool
       *  <img src="/SquarePaint.png" width="100">
       * Select Fill and pick your color
       * Click and drag to create a shape
       * Make sure to remove the outline of the shape
           * Click the outline menu
           * Select the bottom left red diagonal line
           *  <img src="/ZoneOutline.png" width="100"> 
</details>

<details><summary>2. Programming the Paddle</summary>
   
   ##  Adding Code to Paddle [Video Help](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=423s)

   1. Make sure to click on the correct Sprite, "Paddle"
   1. Adding Event Blocks (Yellow) to Paddle [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=490s)
        *  Click on the Correct Sprite - start with "Paddle" [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=500s)
        *  Add the Event Block - "when ___ key pressed"
        *  Change the key so each Event responds to a different key
        *    <img src="/PaddleKey.png" width="200">
        *  One event for each arrow key right and left
              <img src="/PaddleTwoEvents.png" width="400">
   2. Adding Motion Blocks (Blue) [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s)
    

       A.   Change the direction the Paddle points by adding the Motion Block "point in direction __ " [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s) 
       *   Add the movement block to each event - 2 total,
          <img src="/PaddleDirection.png" width="200">
       *   Adjust the direction to face direction of movement [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=545s)
     
       B.    Take Steps by adding "Move __ Steps" block [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=587s)
       *   Check that the 2 events (yellow blocks) have 2 motion blocks (blue) under each them 
          <img src="/PaddleDirectionMove.png" width="300">
       *   That the arrow key matches the direction of the steps [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=644s)

   3.  Test the Paddle Movement!
       *    Does the paddle go left when you hit the left arrow?
       *    Does the paddle go right when you hit the right arrow?
</details>  

<details><summary>3. Code the Ball </summary>    
   
   ### Adding Code to Ball    
Now that the Paddle can be controlled, we want the ball to move around the board.

The Ball should move as soon as we click the green flag to start the game. 
1. Click on the Ball Sprite
2. Adjust the size of the Ball
3. Add an Event Block (yellow)
  * Add the Events Block "when green flag clicked" to the design space. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=740s)

    <img src="/GreenFlag.png" width="150">
4. Add Movement Block (blue)
  * Add "point in direction" under the event block
5. To make the game more fun we are going to add a random direction
  * Add a Operators Block (green)
  * Add "pick random __ to __" to your workspace
  * To have the ball start upward use -90 to 90
  * <img src="/Neg90.png" width="100"><img src="/Neg45.png" width="100"><img src="/Pos45.png" width="100"><img src="/Pos90.png" width="100">
4. Add a Movement Block
  * Add the Movement Block "move __ steps" [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=932s)
  * Recommend starting with 10 steps
     <img src="/BallSteps.png" width="400">

</details>
<details><summary>4. Test your code </summary>   

   ### Test your code       
   1. Do you noticing that Ball moves off the end of the screen if you keep clicking the green flag [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=951s)
       * Keep Ball in the frame by adding the Motion Block "if on edge, bounce" [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=965s)
       <img src="/EdgeBounce.png" width="400">
    2. Would it be nice to not have to hit the green flag all of the time?
</details>
<details><summary>5. Add a Loop </summary>
       
   ### Add a Loop using a Control Block
  
  We want the Movement Block to happen again and again while the game is going, if you test it now it does not [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1009s)
  * A Loop is ideal for this, and we want it to repeat forever while the game is going.
  1. Add a "forever" block (orange) to the workspace [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1009s)
      *<img src="/ForeverDesign.png" width="300">
      * We want this to repeat the movements, but not changing direction
      * Then put the two Movement blocks (blue) "move __ steps"  and "if on edge, bounce" in the grove of the forever loop
      * Then move the whole loop block the under the Event Block (yellow) and the point in Direction Block.
       <img src="/BallMovement.png" width="300">
</details>
<details><summary>5. Ball Bouncing Off Paddle </summary>    
   
   ## Sensing the Paddle
   Now the control for the Paddle and movement for the Ball are set, we'd like to be able to hit the Ball with the Paddle. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1103s)
1. Make sure to still be in the Ball Sprite Work space
2. Add a Sensing Block (turquoise)
   * select the "touching ___" (Sprites)
   * select the Paddle if not selected
4. Add a Control Block (orange)
   * Add the Conditional Block "if __ then"
   * Add the Sensing Block "touching __" into the "if __ then" block. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1200s)
5. Add a Movement Block to Change direction pointing
   * Add the Movement Block "point towards _____" [Video]()
   * Select Sprite1 from block menu
6. Add a Movement Block to take steps  
   * Add the Movement Block "move __ steps"
   * The number chosen should be smaller than the number of steps Sprite1 takes. This number can be adjusted to make the game easier or harder. [Video]()
7. Add a Loop using a Control Block
   * We want the Movement Block to happen again and again while the game is going, so we are adding a loop again.
   * Add a "forever" block (orange) under the Event Block (yellow) then put the Movement blocks (blue) in the grove
<img src="/Parrot_move.png" width="400">
</details>
<details><summary>6. Make the Parrot look like it's flying </summary>    
   
   ### Making the Parrot look like it's flying
1. Add an Events Block [Video]()
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
1. Add an Events Block (yellow) [Video]()
   * Add the Events Block "when green flag clicked" to the design space.
2. Add a Controls Block (orange)
   * Add an "If <> Then" Block [Video]()
3. Add a Sensing Block (Teal)
   * Add "touching ____ " Block into the "If Then" Block. [Video]()
   * Select Crystal from the menu 
4. Add a Sounds Block [Video]()
   * Add a "play sound Meow until done"
5. Add a Loop using a Control Block
   * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop. [Video]()
   * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove.
<img src="/Noise_Sprite1_crystal.png" width="400">
</details>
<details><summary>8. Add sound to Parrot </summary> 
   
   ### Making the Parrot make a sound when it catches Sprite1
1. Add an Events Block (yellow) [Video]()
     * Add the Events Block "when green flag clicked" to the design space.
2. Add a Controls Block (orange)
     * Add an "If <> Then" Block
3. Add a Sensing Block (Teal)
     * Add "touching ____ " Block into the "If Then" Block.
     * Select Sprite1 from the menu 
4. Add a Sounds Block
     * Use the sounds tab to add a new sound. [Video]() 
     * Add a "play sound Meow until done"
     * Change "Meow" to the new sound.
5. Add a Loop using a Control Block
     * We want the sound to happen again and again when the two Sprites touch while the game is going, so we are adding a forever loop again.
     * Add a "forever" block (orange) under the Event Block (yellow) then put the sound blocks (purple) in the grove
   <img src="/Noise_Parrot_Sprite1.png" width="400">
</details>
   
### Trouble Shooting
Try playing your game. Can you change parameters to make it easier or harder? What do you think needs to change? Can you change it?
* Do you want Sprite1 to look like it's walking or running? [Video](=)
       * Add the Looks Block "next costume". [Video]()
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to move faster or slower? 
       * Change the number in the "Move __ Steps" block.  [Video]()
       * Increase to move faster, recommend changing to 20.
       <img src="/Sprite1_nextcostume.png" width="400">
   * Do you want Sprite1 to be larger or smaller, Crystal to be smaller of large?
       * Change the size in the setup area. [Video Sprite]() 
Don't forget to save your game!
   
Let others play your game!
</details>
</details>
<details><summary>Learn about Women in Computer Science</summary>

Watch two videos:
    
[Grace Hopper -- Queen of Code](https://www.youtube.com/watch?v=5sNuPYJpSCI)

[Grace Hooper Written Bio](https://www.womenshistory.org/education-resources/biographies/grace-hopper)

[Ada Lovelace -- First Computer Programer](https://www.youtube.com/watch?v=2vg-0mlSnSE)

[Margaret Hamilton - NASA's First Software Engineer](https://youtu.be/kTn56jJW4zY)
    
[Raye Montague - Interview Naval engineer, and ended up revolutionizing the way ships and submarines are designed](https://youtu.be/1ejoOFulfmQ?si=Ozfe-SOGPAmNoRsE)
    
[Raye Montague - Life story book](https://www.youtube.com/watch?v=maBiBjirKwk)
    
[Fran Kalah - Interview, Pixar Graphic Designer](https://www.khanacademy.org/computing/pixar/crowds/crowds-1/v/meet-fran-kalal)
    
[Isis Anchalee - Computer Engineer and Social Media Activist](https://vimeo.com/212810094)
</details>
<details><summary>Vocabulary</summary>
Algorithm - a set of step-by-step instructions for how to do something, like a recipe
   
Code - a special language created by people to tell a computer what to do

Conditional - used by programmers to get computers to react to different situation, written with IF/ELSE statements

Efficient programs - programs that respond quickly and take less memory and power

ELSE statement - in a conditional when an IF condition is not met, the ELSE action will run

Events - the action the computer is looking for to start a block of code

IF statement - in a conditional when an IF condition is met, the IF action will run

Loop - when a set of instuctions or an algorithm is repeated

Nested Loop - a loop is within a loop

Programming - writing a set of instructions in code

Sequence - order in which things happen
</details>
<h2>Reference</h2>
Using the Juniors - Coding for Good Badge 1 [Grades: 4-5] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=229s)
