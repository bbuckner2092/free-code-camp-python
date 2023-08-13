## Basic Calculator ##

1. I created 2 variables, num1 and num2. With these variables, I included an input() for each so that way the individuals are able to insert two numbers (one for each variable.).
2. In running the basic calculator, I realized that it was not funcitoning properly. It was concatenating the two numbers together. (Side note: In order for us to run the mini-application we had to make sure we were in the terminal and not in python mode. It will not work that way.)
3. Solution: We had to add the int() around the num1 and num2 variables in order to convert the string to numbers. When we have a variable (num1 or num2) python has the cast type as a string. So when we use the + sign it is not adding in an mathmateical way but in a concatenation way. 