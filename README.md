# Snake_Game
This is the classic snake game, made by using python turtle module and concepts of OOP's. 
1. This program contains total 4 .py files and 1 .txt file. In the main.py we keep track of all files and connected them in order to achieve our motive of game.
2. A Graphic User Interface (GUI) is made up by using turtle module, which contains a screen with heading, snake, food, score and high score. This Screen has also a property of exitonclick(), which ensures the user that it only be closed by clicking on it.
3. We further added the screen.listen() function that helps user to control the snake by just pressing keys. We also define three methods to detect collision to wall, food and self, which decides that game will go on or new game will just be started.
4. In snake.py, we made a class using constructor and some methods to create snake, extend it, move it and reset it.
5. In food.py, We create a food of circle shape by using class inheritance, a base class Food which inherit the property of super class Turtle. We also use super().__init__() method to acquire all properties of parent class when initialised.
6. In scoreboard.py, We create a base class Scoreboard of parent class Turtle, which contains some methods like update, increase and reset scoreboard. In reset method, we read the data.txt file in write mode to update the latest high score.
