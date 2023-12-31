# Functions

## Summary:
- A collection of code that performs a specific task.
- Helps you to organize your code better.
- A core concept for programming in python.
- We can give functions information in order to make them more powerful.
- It is good to break your code up into different functions, not just one long function.
- **Parameter:** Additional information that gets passed into the function.

### Creating a function() that says hi to a user.
1. Write def. (It will indicate that this person is wanting to use a function.)
2. Put a space after the word def.
3. write the name of the function. (In this case the function is sayhi).
4.Use parenthesis followed by a colon. 
5. To bring it all together it will look like the following: def sayhi():
6. The code that will go inside of a function, it will **HAVE** to be indented. Python indents 4 spaces exactly.
7. Once indented 4 spaces on the new line, we will write the following: print("Hello User")

### Call the Function After its Created

_Note:_ When we run the file wihtout calling the function, it will have no output. This is why we need to call it. The code inside of a function will only be executed when we specify that we want it to be executed.

1. Type out the name of the function with the open and closed parenthesis.
Example: sayhi(). 
_Note:_ Be sure to save the file prior to running it or else there will be no output.

### The order of Execution in Python

We have the following written out:

def sayhi():
    print("Hello User")

print("Top")
sayhi()
print("Bottom")

The order of execution will be top to bottom. It will run
1. print("Top") first
2. sayhi() function
3. print("Bottom")

### Naming convention for functions:
- In all lower case
- If there is two or more words then use an underscore to seperate them.
- Short names do not technically need an underscore.