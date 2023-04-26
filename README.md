# Reversing-a-string-with-For-loop

# Strings
Strings are used for storing text/characters. For example, "Hello World" is a string of characters. Unlike many other programming languages, C does not have a String type to easily create string variables. Instead, you must use the char type and create an array of characters to make a string in C:

char test[] = "Hello World!";

# Access Strings
Since strings are actually arrays in C, you can access a string by referring to its index number inside square brackets [].

printf("%c", test[0]);

# Algorithm

1.Ask user to input a string to be reversed.
2.Store it in an array.
3.Calculate the length of the string by using the strlen function.
4.Apply a for loop from (counter variable= length-1) initially and decrementing the value till (counter variable>=0) , printing the array in reverse.

![image](https://user-images.githubusercontent.com/125941580/234467297-42c7e9e2-9415-46df-ab00-3f159369b9a3.png)


