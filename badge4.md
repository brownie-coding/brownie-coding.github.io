[Home](/)

# Junior Badge 1 - Coding For Good

<details><summary>Pong</summary>


   
   <details><summary>What is Pong?</summary>     
<p>Pong is a game where you use a paddle to hit a moving ball to defend a space or edge </p>
      
      
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

   4.  Name your program if you signed in.

   5.  Pick a Backdrop from the bottom right corner [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=208s)
        * Any backdrop will work, pick your favorite - you can go back and change this later
        * Program used the "Stripe" Backdrop 
        * Search tool will let you choose from the available backgrounds  
       <img src="/ChooseABackground.png" width="300">

   6.  Pick a Sprite for your Ball [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=250s)

       Clicking on "Choose A Sprite" in the bottom right corner
        * Start typing in the search box to find either a Ball, or your own shape. 
        * Add "Ball"  (or your own choice)
        * Sprite1 (the cat is already picked for you)
        * You can delete this one unless you want to use the cat.
            * Delete it by clicking on the Sprite1, and then the blue trash can on the Sprite1 image.

        <img src="/ChooseASprite.png" width="300">
     
   8. Pick a Sprite for your Paddle [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=288s)
     <p>After clicking on "Choose A Sprite" start typing in the search box to find either a Paddle or your own shape to use as a paddle.</p>

   9. Create a zone to defend by coloring a side of the game area [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=300s)
       * Click on white rectangle in bottom righthand corner that says "Stage"
       * Then click on the Backdrops Tab
       *  <img src="/Backdrops.png" width="300">
       * Select Square paint tool
       *  <img src="/SquarePaint.png" width="100">
       * Select Fill and pick your color
       * Click and drag to create a shape
       * Make sure to make the outline of the shape transparent (invisible)
           * Click the outline menu
           * Select the bottom left red diagonal line
           *  <img src="/ZoneOutline.png" width="100"> 
</details>

<details><summary>2. Programming the Paddle</summary>
   
   ###  Adding Code to Paddle [Video Help](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=423s)

   1. Adding Event Blocks (yellow) to Paddle [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=490s)
        *  Click on the Correct Sprite - start with "Paddle" [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=500s)
        *  Add the Event Block (yellow) - "when ___ key pressed"
        *  Change the selected key so each Event responds to a different key
        *    <img src="/PaddleKey.png" width="200">
        *  One event for each arrow key right and left
              <img src="/PaddleTwoEvents.png" width="400">
   2. Adding Motion Blocks (Blue) [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s)
    

       A.   Change the direction the Paddle points by adding the Motion Block "point in direction __ " [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s) 
       *   Add the movement block to each event - 2 total,
          <img src="/PaddleDirection.png" width="200">
       *   Adjust the direction to face direction of movement [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=545s)
       *   Negative 90 is left
       *   Positive 90 is right
       *   <img src="/Neg90.png" width="100"><img src="/Pos90.png" width="100">
     
       B.    Take Steps by adding "Move __ Steps" block [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=587s)
       *   Check that the 2 events (yellow blocks) have 2 motion blocks (blue) under each them 
          <img src="/PaddleDirectionMove.png" width="300">
       *   That the arrow key matches the direction of the steps you want to be taking [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=644s)

   3.  Test the Paddle Movement!
       *    Does the paddle go left when you hit the left arrow? (or how you wanted it to move?)
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
  * Add "point in direction" to your workspace under the event block
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
  
  A Loop is ideal for this, and we want it to repeat forever while the game is going.
  1. Add a "forever" block (orange) to the workspace [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1009s)

     <img src="/ForeverDesign.png" width="300">
     
      * We want this to repeat the movements, but not changing direction
      * Put the two Movement blocks (blue) "move __ steps"  and "if on edge, bounce" in the grove of the forever loop
      * Then move the whole loop block the under the Event Block (yellow) and the point in Direction Block.
       <img src="/BallMovement.png" width="300">
   2. Test your code!
</details>
<details><summary>6. Ball Bouncing Off Paddle </summary>    
   
   ### Sensing the Paddle
   Now the control for the Paddle and movement for the Ball are set, we'd like to be able to hit the Ball with the Paddle. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1103s)
1. Make sure to still be in the Ball Sprite work space
2. Add a Sensing Block (turquoise)
   * select the "touching ___" (Sprites)
   * select the Paddle if not selected
3. Add a Control Block (orange)
   * Add a conditional using the Control Block "if __ then"
   * Add the Sensing Block "touching __" into the "if __ then" block. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1200s)
4. Add a new Movement Block to take steps  
   * Add the Movement Block "point in direction ___"
   * Add the Operator Block "pick random __ to __ "
   * Use similar numbers as you did for the initial motion
<img src="/PaddleDetect.png" width="400">

5. Test your code!

</details>
<details><summary>7. Add a Sound when hitting the edge you are trying to defend </summary>    
   
   ### Add a sound when you hit the colored zone
1. Make sure to still be in the Ball's workspace [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1360s)
2. Add a Sensing Block (turquoise)
   * select the "touching ___" (color this time)
   * <img src="/ColorSensing.png" width="100">
   * Click on the color on the Sensing block and open the menu, and pick the dropper
   * <img src="/ColorMenu.png" width="200">
   * Use the cursor to select the color from your game are, make sure the outer edge of the cursor is the color of your edge
   * <img src="/SelectionTool.png" width="200">
4. Add a Control Block (orange)
   * Add a new Conditional Block "if __ then" to your workspace
   * Add the Sensing Block "touching _(color)_" into the "if __ then" block. [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1479s)
   * Add the whole "if __ then" block under the first "if __ then" block in your "forever" loop
   * <img src="/IfLoop.png" width="400">
5. Add a Sound Block [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=1560s)
   * Go to the sound tab
   * <img src="/SoundTab.png" width="200">
   * Go to Choose a sound at the bottom left corner
       <img src="/ChooseSound.png" width="200">
   * Example - clicked "Wacky" then "Toy Honk"
   * then add the "start sound _____" block into the "if __ then" block
       <img src="/ToySound.png" width="300">
</details>
<details><summary>8. Add a sound to Ball Bounce on the Paddle </summary>    
   
   ### Making a Sound when the Ball hits the Paddle
   
1. We already have an "if ___ then" block for the Ball touching the paddle
2. Take the Sound Block (pink) "start sound ___"
      * Find a sound for the paddle, either use the "pop" sound already selected or use the Sound tab and pick one
      * Add the pink "start sound ___" block to the "if ___ then" block for the condition when the Paddle and Ball are touching
        <img src="/SoundTwo.png" width="400">   
      
</details>
<details><summary>9. Having the Ball change color </summary> 
   
   ### Making the Ball Change color
   
1. Pick a Looks Block (purple)
    * Take the "change __ effect by __"
    * Defalt of "color" and "25" works, but feel free to play around
    * Add to the conditional that controls the ball touching the paddle
       <img src="/FinalPong.png" width="400">
</details>
<details><summary>10. Trouble Shooting </summary>   

   ### Trouble Shooting
   
Try playing your game. 
    
Can you change parameters to make it easier or harder? 
What do you think needs to change? Can you change it?
   * Do you want Ball to look like it's walking or running? 
   * Add the Looks Block "next costume" under the "move __ steps" block
Do you want Ball or Paddle to move faster or slower?
   * Change the number in the "Move __ Steps" block.
   * Increase to move faster, decrease to move slower
Do you want Ball to be larger or smaller, Paddle to be smaller of large?
    

Don't forget to save your game!
   
Let others play your game!
</details>
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

## Reference

Using the Juniors - Coding for Good Badge 1 [Grades: 4-5] video from STEM for Scouts YouTube Channel 
[Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=229s)
