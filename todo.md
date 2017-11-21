# To-Do
~~- Set window size on load or set game elements to change based on screen size. Possibly used framed game?~~
    - Solution: Set div frame and use css to set size and centering.
    
~~- Add rotating colors on each point (change background image, paddle and ball colors). Look at arrays? Sam's snake game uses this method, i think. Make old ball go away, why does it stay? Re-render canvas?, change pong code?~~
    - Solution: Used array to rotate colors on each point. Fixed the game code to clear the old ball before rendering a new one.
    
~~- Create a winner screen at 5 points? (look at winner screen example, figure out how to get the score and when they equal show screen. can't figure out how to check the score on each point. look into this.)~~
    - Solution: using the point function, it checks the score of the player who just got a point and runs that against the win screen if else.
    
~~- Create changing paddle color gameplay - 3 different paddle shades for each color set - fix subtle colors so you can tell them apart (make it a little easier) - Left and right arrows change color of player a paddle - When correct color, power serve the ball back? (think powerup) - When wrong color, paddle shrinks? - make sure to reset paddle height (100) on point, also reset ball speed (12)!?~~
    - Solution: lots of troubleshooting, help from Brian Bartels, and more troubleshooting and documentation.
    
~~- Change website title to Albers Pong!~~

~~- Make favicon for website~~

##### Stretch Goals
- Create a welcome screen/start screen for the game.
    - look at sam's code
    - look at how to make start screen for js game 
~~- Add "a" and "d" to color changing code? Use if or~~
~~- Fix paddle speed after 1 game~~
~~- Fix paddle speed after game win screen?~~
- Change game font to same 8-bit font


###### (IF YOU RUN OUT OF THINGS TO DO) 
- Fix fuzzy text (google pixi hd or hd javascript text)

~~- Add stroke to score so it is visible when the background is yellow~~

~~- Make paddles and ball bigger~~

