# Return Statement Information

_Summary:_
- Allow Python to return information from a function.
- **Parameters** gives something to the function.
- **Return Statements** gives something back to the user. 
- **Return** breaks the user out of the function. There is no extra code that could be written after it inside of the function. It short circuits once the return completes its task(s).
- You can **return** any type back from the **return** statement.

## Function that Cubes a Number
1. Define the cube definition: def cube():
2. For the parameter, write num
3. After the colon, write out the function that will be taking place: num*num*num
4. Be sure to use the return statement before the num*num*num or else the command line will return none.
_Note:_ We are able to create a variable to house the result of the cube function. We simply do the following:
- Write result = cube(4)
- inside of the print() insert the variable result.
- Result is not running the function but it is storing the result of the function. Since we have 4 as the number for the parameter when we use the print() it will show us 64.