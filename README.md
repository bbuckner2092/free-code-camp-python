# Table of Contents
- **Working with Numbers**
- **Tuples**
- **Mad Libs Game**
- **Lists**
- **List Functions**
- **If Statements**

## Working with Numbers

1. Used the modulus operator to show how remainders work.
2. **abs:** Function used to show the "absolute" value of the number in our function.
3. **pow:** Allows us to raise a number to whatever power we specify.
4. **min:** Allows us to show the min between numbers (or variables) that we have placed within the funciton.

## Tuples

_Summary:_ A type of data structure. It is a container that we can store various values in. Coordinates would be an example of a **tuple.** **Tuples** are immutable, it cannot be changed or modified. What you see is what you get. **Tuples** are index starting at 0.

### Nuance of Tuples
Once we create the tuple, we would not be able to alter it bu using any functions on it or creating a new variable from the original or even using the copy(). It is not allowed to be changed at all. What you have wrote is the only value it could ever be.

### Difference between a List and Tuple

_List_
1. We use [] instead of ().
2. Able to assign various values to it.
Mutate the list as you desire/see fitting.

_Tuple_
1. It is immutable.
2. People use _tuples_ for data taht will never change. It is possible to create a list[] of tuples().

## Mad Libs Game
_Summary:_ A game where you can enter in random words and take all those words to be placed in a story randomly.

1. We need to create 3 variables. 
2. The 1st variable is color which will have an input().
3. The 2nd variable is plurarl_noun which will also have an input().
4. The 3rd variable is celebrity which will also have an input().
5. Once the variables have been created, we then went back into each line of print() in order to replace the curly brackets with the variable names themselves. In addition, we added, removed, and/or relocated the double quotes to make sure that no variable name was inside of the string. Lastly, we have to make sure that we include the plus sign as well.

## Lists
_Summary:_ Lists can be used in the same way as variables. The following are the steps to creating a lists:

1. Give the lists variable a name. Be sure to write down the variable name then = it to [].
2. We added the print() with the variable friends inside of it before hitting run to see the result.
3. **index strings from the list:** We can use [] followed by numerical values inside of the brackets in order to print out specific strings from a lists. 0 is actually the starting position for 1. _To index from the back of the list, you will begin with -1._
4. **Index for several strings/names within a list:** Bu using a colon to seperate the numberical values inside of the square brackets, we are able to get the starting position. _Note: the second numerical value that we provide will nOT be included. It will get the strin/name in the position before it._
5. **Updating names in a lists:** To complete this task, we would need to create a new variable with the same name as the list variable, BUT we have to be sure that we use square brackets with the numerical value that coincides with the name position that we are after. Once we have grabbed that name, the next step is to = the new variable name to the new name which should be inside of double quotes. **Example: friends[1] = "John".**

## List Functions
_Summary:_ Using functions() with list in Python. Some of the msot common and popular functions used on list to make them more easy and powerful to use.

1. **Extend():** Allows you to take a list and append another list to it. Example: **friends.extend(lucky_numbers)** The previous example will literally add the lucky numbers to the end of the friends list.
2. **Append():** Allows you to append specific names/numbers NOT in a list to the lsit you are currenlty using.
3. **Insert():** Takes two parameters, parameter 1 is where you want to insert the item and parameter 2 is where is the the string/name taht will be inserted into the numerical position that was specified in parameter 1.
4. **Remove():** We include the remove function to the friends variable. Be sure to put in double quotes the individual's name that you are wanting to exist now.
5. **Clear():** Gives us an empty list.
6. **Pop():** Removes the last element of the lsit.
7. **Friends.index("string"):** The previous code allows for us to see where in the lista  string/name is positioned at.
8. **Friends.count("string"):** By using this code, we are able to retrieve the # of times a certain string is inside of a list. This is case sensitive.
9. **Friends.sort():** With this code, the list that we have will get sorted in ascending order.
10. **Friends.revers():** This will reverse the sort into descending order.
11. **Friends2 = friends.copy():** The code for this list is just a copy of the original friends variable.

## If Statements
_Summary:_ Helps our program to make decisions.

- Allows the program to respond to the input that is given.
- Programs are becoming a lot smarter.
- If conditions are true, then we take a certain action. If those conditions are false then there will be a different action taken.
- With these examples in this markdown, the if statements become more complex.
-If statement have to be reduced down to either a true or false evaluaiton.
-Else will be used as our "otherwise".

### A Boolean Variable that is going to store whether a user is a male or not

1.) Created a variable (is_male) that was equal to True.
2.) Wrote out the following if statement -> if is_male:
3.) Under the if statment, included code that would run IF the variable was in fact true. It was the following code -> Print("You are a male")