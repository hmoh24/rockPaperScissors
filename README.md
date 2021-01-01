# rockPaperScissors
This is my first Javascript project. I will be using this to practice my implementation of basic javascript theory. I have used variables, functions, conditional statements and operators, and while loops in this project. I ran into many problems in this short project. I had to breakdown the problem into smaller chunks and deal with each one separately. An example of a problem would be my inability to create a function that chooses a random object in an array. I had to search google to figure this out since my course did not cover this. 

I also had problems with my while loop which was also not covered in my basic javascript theory. The functionality of the while loop itself was not the problem, but I had it set up to run the game until a player reached 5 total score, but the game was incorrectly repeating the result of the previous score. It was challenging to try and figure out why my code was not doing what it was supposed to, but by using console.log to track the results of my code, I successfully narrowed it down to the while loop. Once inside the while loop, I used console.log to help pinpoint what the error was. The error stemmed from an incorrect use of functions. I had not set the parameters for a function, therefore in my loop it was repeating the result of the first run of the game over and over, no matter the input from me or the computer. All in all, it was challenging, but ultimately rewarding to successfully conquer my first javascript project. 


I came back to this roughly two weeks later to add an interface so that the game is not played through prompts or the console. I have added CSS which I am fairly comfortable with now. However, my design skills need to be improved. The main prupose of adding an interface was to develop my skills with javascript which at first was extremely challenging. 

Creating functions and loops are more comfortable to me now after practice, but manipulating the DOM, which is a large part of javascript, is more difficult. It represents a new way of programming for me, and although I managed to complete this project, reading through my javascript code I can see problems. For example, there is a lot of copied and pasted code in the buttons. I found it difficult to make it work any other way, but in the future I would like to reduce the amount of repeated code as much as possible.

Improvements:

As I am writing the code for my next javascript project, I have figured out how to reduce the repeated code in this project. I was uncertain of how to 'link' the buttons and the game logic without this repeated code, but now I recognise that the repeated code is essentially the same function in the event handlers of the buttons. I must extract this function, give it a name, and simply slot it into the event handlers of all three buttons. I will aim to refactor this some point in the future.


