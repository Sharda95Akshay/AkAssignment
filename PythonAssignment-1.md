## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans. Because they are not written in machine-readable language, Python programs need to be processed before machines can run them. Python is an interpreted language. This means that every time a program is run, its interpreter runs through the code and translates it into machine-readable byte code.

Q2. Why is Python called a dynamically typed language?
Ans. Python is a dynamically typed language. What is dynamic? We don't have to declare the type of a variable or manage the memory while assigning a value to a variable in Python. Other languages like C, C++, Java, etc.., there is a strict declaration of variables before assigning values to them. We have to declare the kind of variable before assigning a value to it in the languages C, C++, Java, etc

Q3. List some pros and cons of Python programming language?
Ans. Pros:
1. Beginner-Friendly 
2. Large Community
3. Flexible and Extensible
4. Extensive Libraries 
5. Embeddable
6. Highly Scalable
7. IOT Opportunities
8. Machine Learning
9. Portable

Cons:
1. Issues with Design
2. Slower than Compiled Languages
3. Security
4. Work Environment
5. Python’s Memory Consumption and Garbage Collection
6. Python is Dynamically Typed
7. Multithreading in Python.
  
Q4. In what all domains can we use Python?
Ans. 1) Machine learning / Artificial intelligence
2) Desktop GUI
3) Data analytics and data visualization 
4) Web development
5) Game development
6) Mobile app development
7) Embedded systems
Q5. What are variable and how can we declare them?
Ans. A variable is a name given to a specific memory location.
ex: abc = 10
Q6. How can we take an input from the user in Python?
Ans. abc = input()
Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. String
Q8. What is type casting?
Ans. Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans. No.
Q10. What are keywords?
Ans. Python keywords are special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes. These keywords are always available—you’ll never have to import them into your code.
Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase and they must be written as they are
Q12. What is indentation? What's the use of indentaion in Python?
Ans. Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.
Q13. How can we throw some output in Python?
Ans. Python developer you can choose to throw an exception if a condition occurs.
Q14. What are operators in Python?
Ans. Operators are used to perform operations on variables and values.
Arithmetic operators
Assignment operators
Comparison operators
Logical operators
Identity operators
Membership operators
Bitwise operators
Q15. What is difference between / and // operators?
Ans. / for float divison
	// for integer divison
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. a1 = "iNeuron"*4
print(a1)
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans. num = int(input())
	if(num%2==0):
	print("number is even")
	else:
	print("number is odd")
Q18. What are boolean operator?
Ans. Boolean operator are True and False.
Q19. What will the output of the following?
```
1 or 0  

0 and 0

True and False and True

1 or 0 or 0
```
Ans. 1 or 0 ---- 1 

0 and 0   ---- 0

True and False and True   ---- False

1 or 0 or 0    ---- 1
Q20. What are conditional statements in Python?
Ans. Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean constraint evaluates to true or false. Conditional statements are handled by IF statements in Python.
1) if statement.
2) if...else statement

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans. If the condition for if is False, it checks the condition of the next elif block and so on.If all the conditions are False, the body of else is executed.
Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans. age = int(input())
	if(age >= 18):
	print("I can vote")
	else:
	print("I can't vote").
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```