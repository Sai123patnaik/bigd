## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?

Ans) Not only python but all coding languages are high-level because it is in human readable and text format with some syntax and not understood by computer.

Q2. Why is Python called a dynamically typed language?

Ans) Because we don't need to declare variable type, it understands by itself.

Q3. List some pros and cons of Python programming language?

Ans) Pros:-It is dynamic in nature; abundant libraries for tackling ML and data; simple to code; 
 
     Cons:-


Q4. In what all domains can we use Python?

Ans.) Python is more used in Data Analytics domain like ML, AI and Deep learning.

Q5. What are variable and how can we declare them?

Ans.) variables are names used for memory allocations for storing values, we can declare them by using alphabets and number combination with underscore as well;

Q6. How can we take an input from the user in Python?

Ans.)by using input function

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans.)string

Q8. What is type casting?

Ans.)converting data type to another data type

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans.)yes we can by using the .split () function

Q10. What are keywords?

Ans.)Keywords are inbuilt python words used for specific function. There are 35 keywords in python.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans.) No we can't use keywords as a variable, python will throw error if we do it.

Q12. What is indentation? What's the use of indentaion in Python?

Ans.)Python follows indentation space for identifying the code, it maintains proper structure and easy to read and execute as well.

Q13. How can we throw some output in Python?

Ans.) using print function

Q14. What are operators in Python?

Ans.) there are Arthimetic operators like +,-,/,*,//,%
        comparison ==,!=,>,<,>=,<=
        assignment operator =,

Q15. What is difference between / and // operators?

Ans.)/ will do floating divison and // used for integer divison

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

print("iNeuron"*3)
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

a=int(input("please enter a number:"))

if a%2==0:
    print("Even")
else:
    print("odd")
    

Q18. What are boolean operator?

Boolean operators are True and False

Q19. What will the output of the following?
```
1 or 0>>1

0 and 0>>0

True and False and True>>false

1 or 0 or 0>>1
```

Q20. What are conditional statements in Python?

A.) if, else, elif are conditional statements.

Q21. What is use of 'if', 'elif' and 'else' keywords?

A.) if checks a condition and prints if condition is met or passes it to elif which again validates a different condition and prints if evaluated condition is true and finally else statement is used as default.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

A.) age=int(input("Enter age of a person:"))
    if age>=18:
        print("I can vote")
    else:
        print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]

sum=0

for i in numbers:
    if i%2==0:
        sum+=i
print(sum)    

```
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans.)Num1=int(input("Enter num1:"))
    Num2=int(input("Enter num2:"))
    Num3=int(input("Enter num3:"))
    if Num1>Num2 and Num1 > Num3:
        print("Num1 is greatest", Num1)
    elif Num2>Num3:    
        print("Num2 is greatest", Num2)
    else:
        ("Num3 is greatest", Num3)
        
        

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i%5==0:
        if i > 150 and i <=500:
            continue
        elif i > 500:
            break
        else:
            print(i)





```