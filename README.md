Checking whether a Character is Alphabet or Not in Python ?
Here, we will discuss program to check whether a Character is alphabet or not in python .All characters whether alphabet, digit or special character have ASCII value. Input character from the user will determine if it’s Alphabet, Number or Special character.

Character is an alphabet or not in python

Explanation
In C programming language a char type variable can store many different types of characters-

Alphabets (a, b, c… )
Digits(1, 2, 3…)
Special characters(@, %, &…)
These characters are differentiated on the basis of ASCII values :

between 65 and 90 for upper case(A, B, C…)
between 97 and 122 for lower case(a, b, c…)
In here we will see how to identify whether a character is alphabet or not using C++ programming language.

Working
Get user input
Check if input is between ‘A'(65) – ‘Z'(90) or between ‘a'(96) – ‘z'(122)
If True print ‘Yes’
If False print ‘No’
Python Program to check whether a character is an alphabet or not
Python code (method 1)
Run
# Python Program to find character is alphabet or not

# user input
ch = 'z'

# basic logic
if 'a' <= ch <= 'z' or 'A' <= ch <= 'Z':
    print("The  character", ch, "is an Alphabet")
else:
    print("The  character", ch, "is not an Alphabet")
Output
The  character z is an Alphabet

Method 2
You can also check the alphabet using the ASCII values of characters like this:
In Python ord() function is used to get ascii value of any character in python.
if 97 <= ord(ch) <= 122 or 65 <= ord(ch) <= 90:
    print("The inserted character", ch, "is an Alphabet")
else:
    print("The inserted character", ch, "is not an Alphabet")
Python code (method 2)
Run
# Python Program to find character is alphabet or not

# user input
ch = 'z'

# basic logic
if 97 <= ord(ch) <= 122 or 65 <= ord(ch) <= 90:
    print("The character", ch, "is an Alphabet")
else:
    print("The character", ch, "is not an Alphabet")
Output
The character z is an Alphabet
