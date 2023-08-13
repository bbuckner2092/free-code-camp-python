# Tuples 

_Summary:_ 
A type of data structure. It is a container that we can store various values in. Coordinates would be an example of a tuple. Tuples are immutable, it cannot be changed or modified. What you see is what you get. Tuples are index starting at 0.

## Nuance of Tuples
Once we create the tuple, we would not be able to alter it by using any functions on it or creating a new variable fromt he original or even using the copy(). It is not allowed to be changed at all. What you have initially wrote is the only value it could ever be.

### Difference between a List and Tuple
_List_
1. We use [] instead of ().
2. Able to assign various values to it.
3. Mutate the list as you desire/see fitting.

_Tuple_
1. We cannot do 1-3 in tuple. It is immutable.
2. People use tuples for data that will ever change.
It is possible to create a list[] of tuples().