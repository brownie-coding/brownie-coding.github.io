[Home](/)

# Junior Badge 1 - Coding For Good
<details><summary><h2>Pong</summary></h2></summary>
<details><summary><h3>What is Pong?</h3></summary>     
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
<details><summary><h3>Creating a Pong Game</h3></summary>   
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
        * Sprite1 (the cat is already picked for you)
        * You can delete this one unless you want to use the cat.
            * Delete it by clicking on the Sprite1, and then the blue trash can on the Sprite1 image.
        * Add Ball (or your own choice)

        <img src="/ChooseASprite.png" width="300">
     

   7. Pick a Paddle Sprite
     <p>After clicking on "Choose A Sprite" start typing in the search box to find either a Paddle or your own shape.</p>

   8. Create a zone to defend
       * Click on white rectangle in bottom righthand corner that says "Stage"
       * Then click on the Backdrops Tab
       * Select Square paint tool
       * Select Fill and pick your color
       * Click and drag to create a shape
       * Make sure to remove the outline of the shape
           * Click the outline menu
           * Select the bottom left red diagonal line   
</details>

<details><summary>2. Programming the Paddle</summary>
   
   ##  Adding Code to Paddle [Video Help](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=423s)

   1. Make sure to click on the correct Sprite, "Paddle"
   1. Adding Event Blocks (Yellow) to Ball [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=490s)
        *  Click on the Correct Sprite - start with "Paddle" [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=500s)
        *  Add the Event Block - "when ___ key pressed"
        *  Change the key so each Event responds to a different key
        *    <img src="/PaddleKey.png" width="300">
        *  One event for each arrow key right and left
        *    <img src="/PaddleTwoEvents.png" width="300">
   2. Adding Motion Blocks (Blue) [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s)
    
    
       A.   Change the direction the Paddle points by adding the Motion Block "point in direction __ " [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=524s) 
       *   Add the movement block to each event - 2 total,
       *   <img src="/PaddleDirection.png" width="400">
       *   Adjust the direction to face direction of movement [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=545s)
     
       B.    Take Steps by adding "Move __ Steps" block [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=587s)
       *   Check that the 2 events (yellow blocks) have 2 motion blocks (blue) under each them 
       *   <img src="/PaddleDirectionMove.png" width="400">
       *   That the arrow key matches the direction of the steps [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=208s)

   3.  Test the Paddle Movement! 
</details>  

<details><summary>3. Code the Ball </summary>    
   
   ## Adding Code to Ball    
Now that the Paddle can move around we'd like the ball to move around the board.

We would like this event to start as soon as we click the green flag. 
1. Click on the Ball
2. Adjust the size of the Ball
3. Add an Event Block (yellow)
  * Add the Events Block "when green flag clicked" to the design space. [Video]()
  *   <img src="/GreenFlag.png" width="400">
4. Add Movement Block (blue)
  * Add "point in direction" under the event block
4. Add a Movement Block
  * Add the Movement Block "glide one secs to random position" [Video]()
5. Add a Loop using a Control Block
  * We want the Movement Block to happen again and again while the game is going, if you test it now it does not [Video]()
  * A Loop is ideal for this. [Video]()
  * Add a "forever" block (orange) [Video]() under the Event Block (yellow) then put the Movement block (blue) in the grove [Video]()
<img src="/Crystal_loop.png" width="400">
</details>
<details><summary>4. Test your code </summary>   

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
</details>
<details><summary><h2>Learn about Women in Computer Science</h2></summary>

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
<details><summary><h2> Vocabulary</h2></summary>
Events - the action the computer is looking for to start a block of code
</details>
<h2>Reference</h2>
Using the Juniors - Coding for Good Badge 1 [Grades: 4-5] video from STEM for Scouts YouTube Channel [Video](https://www.youtube.com/watch?v=GeyjtKVWkx4&t=229s)
