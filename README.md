# RURPLE-Final-Project
Here is The Description of the Game
“Cat & Rat”
In this code we import tow pics for the rat and the cat :

Cat 

Rat


Background: 

We import ‘pygame, sys’ then create a window has a width and height that =500, 7 tiles and the tiles have width and height = (width/tiles+ spaces(variables)) and that window called “cat& rat”
We are using white, black, aqua, green and yellow colors, and there are variables for (board, water, and bridge) then put “water in the position"
Frame height = frame width = (width-2*variable tile x +5) and the frame = (height, width) and the color of the frame background is white and his rectangle =tile x -2



The function board rectangles has (a variable called a rectangle=initial x ,initial y ,tile x, tile y) So if(x,y) in the water area the a rectangle will append ,(3,6) a rectangle will append In bridge area else that a rectangle will append in the board area and the line separate the tiles
•	Function draw board that for give a color for each area
Loop while true: the pack ground for the window is black and update any change


This code is representing for the random movement of the cat and rat, so we have some cases like the winning case and the losing case, and the random variable is the rat move only by one step, the movement is only step for right or left or up or down, so in the winning case when the rat reach to the bridge, the screen will fill by the green color, in the losing case, when the rat go to any rectangle of the water places the screen will fill with the Aqua color , when the rat move for 20 steps and the rat failed to reach the bridge then the program is out.
This code is representing the move of the rat by Arrows not a random variable and the move is by one step so when the Up arrow is clicked the rat move to up , when the Down arrow is clicked , the rat move to Down , when the Left arrow is clicked , the rat move to left , when the Right arrow is clicked the rat move one step to Right.  


