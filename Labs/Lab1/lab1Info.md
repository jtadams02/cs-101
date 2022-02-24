# Lab 1
# 2.34 LAB: Warm up: Variables, input, and casting

(1) Prompt the user to input an integer, a double, a character, and a string, storing each into separate variables. Then, output those four values on a single line separated by a space. (2 pts)  
  
_Note: This zyLab outputs a newline after each user-input prompt. For convenience in the examples below, the user's input value is shown on the next line, but such values don't actually appear as output when the program runs._

```
Enter integer:
99
Enter double:
3.77
Enter character:
z
Enter string:
Howdy
99 3.77 z Howdy

```

  
(2) Extend to also output in reverse. (1 pt)

```
Enter integer:
99
Enter double:
3.77
Enter character:
z
Enter string:
Howdy
99 3.77 z Howdy
Howdy z 3.77 99

```

  
(3) Extend to cast the double to an integer, and output that integer. (2 pts)

```
Enter integer:
99
Enter double:
3.77
Enter character:
z
Enter string:
Howdy
99 3.77 z Howdy
Howdy z 3.77 99
3.77 cast to an integer is 3

```

# 3.28 LAB: Name format

Instructor note:

Guide:

1.  Use `getline(cin, str);` to read the line of input into a `string`.
2.  Determine the number of spaces and conditionally output the appropriate information.
3.  It will be helpful to build strings of the first, middle, and last names. Remember the string methods:
    -   substr()
    -   find()
    -   += (append)
    -   [ ] (access a char)

Many documents use a specific format for a person's name. Write a program whose input is:

firstName middleName lastName

and whose output is:

lastName, firstInitial.middleInitial.

Ex: If the input is:

```
Pat Silly Doe

```

the output is:

```
Doe, P.S.

```

If the input has the form: firstName lastName

the output is:

lastName, firstInitial.

Ex: If the input is:

```
Julia Clark

```

the output is:

```
Clark, J.

```

# 5.20 LAB: Output values below an amount

Write a program that first gets a list of integers from input. The input begins with an integer indicating the number of integers that follow. Then, get the last value from the input, which indicates a threshold. Output all integers less than or equal to that last threshold value.

Ex: If the input is:

```
5 50 60 140 200 75 100

```

the output is:

```
50,60,75,

```

The 5 indicates that there are five integers in the list, namely 50, 60, 140, 200, and 75. The 100 indicates that the program should output all integers less than or equal to 100, so the program outputs 50, 60, and 75.

For coding simplicity, follow every output value by a comma, including the last one.

Such functionality is common on sites like Amazon, where a user can filter results.

# 6.21 LAB: Warm up: Text analyzer & modifier

(1) Prompt the user to enter a string of their choosing. Output the string. (1 pt)  
  
Ex:

```
Enter a sentence or phrase:
The only thing we have to fear is fear itself.

You entered: The only thing we have to fear is fear itself.

```

(2) Complete the GetNumOfCharacters() function, which returns the number of characters in the user's string. _We encourage you to use a for loop in this function._ (2 pts)

(3) In main(), call the GetNumOfCharacters() function and then output the returned result. (1 pt)

(4) Implement the OutputWithoutWhitespace() function. OutputWithoutWhitespace() outputs the string's characters except for whitespace (spaces, tabs). Note: A tab is '\t'. Call the OutputWithoutWhitespace() function in main(). (2 pts)  
  
Ex:

```
Enter a sentence or phrase:
The only thing we have to fear is fear itself.

You entered: The only thing we have to fear is fear itself.

Number of characters: 46
String with no whitespace: Theonlythingwehavetofearisfearitself.

```
