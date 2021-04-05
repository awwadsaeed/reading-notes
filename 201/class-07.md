# Object-Oriented Programming, HTML Tables
## HTML tabels  
you can create tables by using the `<table></table>` tags you start by defining rows with the `<tr></tr>` tags and each elemnt in the row is a `<td></td>`tag.  
## Object-oriented programming  
befor object oriented programming the process of programming was linear. lets say that i am making a game,
and im making the player character then i have to make a variable for each information that is rlated to that player like player position in the x axis and in the y axis the player's hp and the list goes on and on, and to control those properties ill make a function for them it would be like:  
function move (x,y){  
    x=x+1;
    y=y+1;  
}  
for each step he moves, and i have to call the function like this:  
move(playerXPos,playerYPos)  
and if i want to make another player i have to do it all over again in the code in the place where the second player will appear in the game same goes for enemies but with object oriented programming all i have to do was create a template which is called objects in javascript (classes in c++) and instantiate an instance of that object and thats all i dont have to recreat the variables all over again and when the player moves for example all i have to do is call the method like  (lets call the player a player1 for example):  
player1.move();  
and if i create another player (player2 for example):  
player2.move();  
which is much shorter and easier to do.  