By now you have mastered number, boolean, and string literals, expressions, statements, assignment, while loops, function definitions, and function calls. 
Now its time for arrays.

An array is a kind of list. You can create one with square brackets. Here's an example:
```javascript
my_array = [1,2,3,4,5];
```

Now you can refer to the individual elements in the array using their position (again, with square brackets). This is called "dereferencing" the array. Try this:
```javascript
my_array = [1,2,3,4,5];
print(my_array[3]);
print(my_array[0]);
```
Notice that the first position in the array is numbered 0, and not 1. There is one MAJOR difference between arrays and the other other type of data we have used before. They have what's called "reference semantics" as opposed to "copy semantics". This means that when they are assigned to a variable, passed as parameters, or used as return values, they are NOT copied. They simply get a new alias.
