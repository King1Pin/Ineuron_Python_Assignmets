## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans 1.Python is a general-purpose language because it can be used to create a variety of different programs and isn't specialized for any specific problems.
 
Q2. Why is Python called a dynamically typed language?
Ans 2. Python is dynamically typed launguage because it does not require any pre-defined data type to be declared for any variable and it interpreted the datatype of the variable at runtime depending upon the value.

Q3. List some pros and cons of Python programming language?
Ans 3. Pros of Python is that it is an easy to use programming launguage with a smooth learning curve. Python supports both procedural and object-oriented programming which makes is flexible. A python program is only require to write once and can be run anywhere and the complilation happens during runtime. Python also has a huge third-party library support and it an open source software.

Cons of python is that it is generally slower than other launguage like C and Java. It also tends to use more memory when compared with other languages. Since python is dynamically typed it is harder to avoid the runtime erros.

Q4. In what all domains can we use Python?
Ans 4. Employing python allows the user to work on multiple domains ranging from Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game Development to Web Development.

Q5. What are variable and how can we declare them?
Ans 5. Declaration of a variable in a computer programming language is a statement used to specify the variable name and its data type. Declaration tells the compiler about the existence of an entity in the program and its location. When you declare a variable, you should also initialize it.

Q6. How can we take an input from the user in Python?
Ans 6. input (): This function first takes the input from the user and converts it into a string. The type of the returned object always will be <class 'str'>. It does not evaluate the expression it just returns the complete statement as String.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Python takes all the input as a string input by default. To convert it to any other data type, we have to convert the input explicitly.

Q8. What is type casting?
The conversion of one data type into the other data type is known as type casting in python or type conversion in python. Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes we can take more than one input using single input() function. We need to use split function with input function to take multiple inputs. 

Example : a, b, c = input("Enter three values: ").split()

Q10. What are keywords?
Ans 10. Keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes. These keywords are always available—you'll never have to import them into your code. Python keywords are different from Python's built-in functions and types.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans 11. We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase and they must be written as they are.

Q12. What is indentation? What's the use of indentaion in Python?
Python indentation refers to adding white space before a statement to a particular block of code. In another word, all the statements with the same space to the right, belong to the same code block.

Python uses indentation to highlight the blocks of code. Whitespace is used for indentation in Python. All statements with the same distance to the right belong to the same block of code. If a block has to be more deeply nested, it is simply indented further to the right.

Q13. How can we throw some output in Python?
Ans 13. We can show output in Pythong using print() function. 
Example : print("Hope you are doing well!")

Q14. What are operators in Python?
And 14.  In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands. Here is an example: >>> >>> a = 10 >>> b = 20 >>> a + b 30. In this case, the + operator adds the operands a and b together.

Q15. What is difference between / and // operators?
Ans 15. Using "/" single slash carries out normal float division. The output of this operator is always a quotient with a float datatype.

Using "//" double slash in division with perform the division but quotient will be an integer value. The value of the quotient is always rounded off to the lowest interger value. 

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans 16. print("iNeuroniNeuroniNeuroniNeuron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans 17. 

inpNum = int(input("Enter a number: "))

if inpNum % 2 == 0:
    print(inpNum, "is even")
else:
    print(inpNum, "is odd")
	

Q18. What are boolean operator?
Boolean Operators are those that result in the Boolean values of True and False. These include and, or and not. While and & or require 2 operands, not is a unary operator. Boolean operators are most commonly used in arithmetic computations and logical comparisons.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans 19. 1 or 0 -> 1

0 and 0 -> 0

True and False and True -> False

1 or 0 or 0 -> 1

Q20. What are conditional statements in Python?
And 20 : if, else and elif are three conditional statements in Python.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans 21. 'if' is used to check a specific condition or a combination of conditions and if outcome of the conditions is 'true' then the code inside the 'if' block is executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans 22. Below is the program

age = int(input("Enter your age: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans 23. Below is the program to check if the given number are even or not.
numbers = [12, 75, 150, 180, 145, 525, 50]

sum = 0

for num in numbers:
    if num % 2 == 0:
        sum += num

print("The sum of all the even numbers is", sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans 24. Below is the program to check the greatest number.

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
num3 = int(input("Enter the third number: "))

maxNum = max(num1, num2, num3)

print("The greatest number is", maxNum)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Q26. What is a string? How can we declare string in Python?

Q27. How can we access the string using its index?

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```

Q30. Resverse the string given in the above question.

Q31. How can you delete entire string at once?

Q32. What is escape sequence?

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```

Q34. What is a list in Python?

Q35. How can you create a list in Python?

Q36. How can we access the elements in a list?

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 

Q38. Take a list as an input from the user and find the length of the list.

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```

Q40. What is a tuple? How is it different from list?

Q41. How can you create a tuple in Python?

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Q44. Take a tuple as an input and print the count of elements in it.

Q45. What are sets in Python?

Q46. How can you create a set?

Q47. Create a set and add "iNeuron" in your set.

Q48. Try to add multiple values using add() function.

Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Q52. How is frozen set different from set?

Q53. What is union() in sets? Explain via code.

Q54. What is intersection() in sets? Explain via code.

Q55. What is dictionary ibn Python?

Q56. How is dictionary different from all other data structures.

Q57. How can we delare a dictionary in Python?

Q58. What will the output of the following?
```
var = {}
print(type(var))
```

Q59. How can we add an element in a dictionary?

Q60. Create a dictionary and access all the values in that dictionary.

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Q62. What is the use of get() function?

Q63. What is the use of items() function?

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?


### Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```