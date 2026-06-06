# Practical Assignment - 1
---

## Q1. Create a program that checks whether a person is eligible to vote.

### Code

```
age = int(input("Enter your age: "))

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
```

### Output

```
Enter your age: 20
You are eligible to vote.
```

---

## Q2. Check whether a number is positive.

### Code

```
num = int(input("Enter a number: "))

if num > 0:
    print("Positive Number")
else:
    print("Not a Positive Number")
```

### Output

```
Enter a number: 15
Positive Number
```

---

## Q3. Check whether an employee is eligible for a bonus if the salary is less than ₹30,000.

### Code

```
salary = float(input("Enter salary: "))

if salary < 30000:
    print("Eligible for Bonus")
else:
    print("Not Eligible for Bonus")
```

### Output

```
Enter salary: 25000
Eligible for Bonus
```

---

## Q4. Check whether a student has passed if marks are greater than or equal to 40.

### Code

```
marks = int(input("Enter marks: "))

if marks >= 40:
    print("Pass")
else:
    print("Fail")
```

### Output

```
Enter marks: 55
Pass
```

---

## Q5. Check whether a number is even or odd.

### Code

```
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### Output

```
Enter a number: 8
Even
```

---

## Q6. Check whether a person can enter a movie theatre if age is 18 years or above.

### Code

```
age = int(input("Enter age: "))

if age >= 18:
    print("Allowed to enter")
else:
    print("Not allowed")
```

### Output

```
Enter age: 21
Allowed to enter
```

---

## Q7. Create a login verification system that grants access only when the username is "admin".

### Code

```
username = input("Enter username: ")

if username == "admin":
    print("Access Granted")
else:
    print("Access Denied")
```

### Output

```
Enter username: admin
Access Granted
```

---

## Q8. Check whether a customer qualifies for free delivery if the order amount is ₹500 or more.

### Code

```
amount = float(input("Enter order amount: "))

if amount >= 500:
    print("Free Delivery")
else:
    print("Delivery Charges Apply")
```

### Output

```
Enter order amount: 700
Free Delivery
```

---

## Q9. Create a grading system using the following criteria:
- Marks ≥ 90 → Grade A
- Marks 80–89 → Grade B
- Marks 70–79 → Grade C
- Marks < 70 → Grade D

### Code

```
marks = int(input("Enter marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 80:
    print("Grade B")
elif marks >= 70:
    print("Grade C")
else:
    print("Grade D")
```

### Output

```
Enter marks: 85
Grade B
```

---

## Q10. Create a simple calculator that performs Addition, Subtraction, Multiplication, and Division using menu selection.

### Code

```
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = int(input("Enter choice: "))

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if choice == 1:
    print("Result =", a + b)
elif choice == 2:
    print("Result =", a - b)
elif choice == 3:
    print("Result =", a * b)
elif choice == 4:
    print("Result =", a / b)
else:
    print("Invalid Choice")
```

### Output

```
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter choice: 1
Enter first number: 10
Enter second number: 5
Result = 15
```

---
## Q11. Classify electricity consumption into:
- 0–100 Units → Low
- 101–300 Units → Medium
- Above 300 Units → High

### Code

```
units = int(input("Enter electricity units: "))

if units <= 100:
    print("Low")
elif units <= 300:
    print("Medium")
else:
    print("High")
```

### Output

```
Enter electricity units: 250
Medium
```

---

## Q12. Classify annual income into:
- Below ₹3,00,000 → No Tax
- ₹3,00,000 to ₹7,00,000 → Basic Tax
- Above ₹7,00,000 → Higher Tax

### Code

```
income = float(input("Enter annual income: "))

if income < 300000:
    print("No Tax")
elif income <= 700000:
    print("Basic Tax")
else:
    print("Higher Tax")
```

### Output

```
Enter annual income: 500000
Basic Tax
```

---

## Q13. Rate internet speed.

### Code

```
speed = float(input("Enter speed in Mbps: "))

if speed > 100:
    print("Excellent")
elif speed >= 50:
    print("Good")
elif speed >= 10:
    print("Average")
else:
    print("Poor")
```

### Output

```
Enter speed in Mbps: 75
Good
```

---

## Q14. Create a loan eligibility checker.

### Code

```
age = int(input("Enter age: "))
salary = float(input("Enter salary: "))

if age >= 21 and salary >= 25000:
    print("Eligible for Loan")
else:
    print("Not Eligible")
```

### Output

```
Enter age: 25
Enter salary: 30000
Eligible for Loan
```

---

## Q15. Create a college admission verification system.

### Code

```
marks = int(input("Enter marks: "))
age = int(input("Enter age: "))

if marks >= 60 and age <= 25:
    print("Admission Approved")
else:
    print("Admission Rejected")
```

### Output

```
Enter marks: 75
Enter age: 20
Admission Approved
```

---

## Q16. Create an e-commerce premium membership checker.

### Code

```
amount = float(input("Enter purchase amount: "))
status = input("Membership Status (Yes/No): ")

if amount > 5000 and status == "Yes":
    print("Premium Membership Eligible")
else:
    print("Not Eligible")
```

### Output

```
Enter purchase amount: 7000
Membership Status (Yes/No): Yes
Premium Membership Eligible
```

---

## Q17. Create a company hiring eligibility system.

### Code

```
graduation = input("Graduation Completed (Yes/No): ")
experience = int(input("Enter experience in years: "))

if graduation == "Yes" and experience >= 2:
    print("Eligible for Hiring")
else:
    print("Not Eligible")
```

### Output

```
Graduation Completed (Yes/No): Yes
Enter experience in years: 3
Eligible for Hiring
```

---

## Q18. Print numbers from 1 to 20 using a while loop.

### Code

```
i = 1

while i <= 20:
    print(i)
    i += 1
```

### Output

```
1
2
3
...
20
```

---

## Q19. Print numbers from 20 to 1 using a while loop.

### Code

```
i = 20

while i >= 1:
    print(i)
    i -= 1
```

### Output

```
20
19
18
...
1
```

---

## Q20. Print all even numbers between 1 and 50 using a while loop.

### Code

```
i = 2

while i <= 50:
    print(i)
    i += 2
```

### Output

```
2
4
6
...
50
```

---

## Q21. Print the multiplication table of a given number using a while loop.

### Code

```
num = int(input("Enter a number: "))

i = 1
while i <= 10:
    print(num, "x", i, "=", num * i)
    i += 1
```

### Output

```
Enter a number: 5
5 x 1 = 5
...
5 x 10 = 50
```

---

## Q22. Find the sum of the first N natural numbers.

### Code

```
n = int(input("Enter N: "))

i = 1
total = 0

while i <= n:
    total += i
    i += 1

print("Sum =", total)
```

### Output

```
Enter N: 5
Sum = 15
```

---

## Q23. Print numbers from 1 to 100 using a for loop.

### Code

```
for i in range(1, 101):
    print(i)
```

### Output

```
1
2
3
...
100
```

---

## Q24. Print all odd numbers between 1 and 100.

### Code

```
for i in range(1, 101, 2):
    print(i)
```

### Output

```
1
3
5
...
99
```

---

## Q25. Print the square of numbers from 1 to 10.

### Code

```
for i in range(1, 11):
    print(i, "=", i * i)
```

### Output

```
1 = 1
2 = 4
...
10 = 100
```

---

## Q26. Generate multiplication tables from 1 to 10.

### Code

```
for i in range(1, 11):
    print("\nTable of", i)

    for j in range(1, 11):
        print(i, "x", j, "=", i * j)
```

### Output

```
Table of 1
1 x 1 = 1
...
Table of 10
10 x 10 = 100
```

---

## Q27. Display all numbers between 1 and 100 divisible by both 3 and 5.

### Code

```
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print(i)
```

### Output

```
15
30
45
60
75
90
```

---

## Q28. Find the sum of all even numbers between 1 and 100.

### Code

```
total = 0

for i in range(2, 101, 2):
    total += i

print("Sum =", total)
```

### Output

```
Sum = 2550
```

---

## Q29. Accept numbers until 0 is entered and count positive numbers.

### Code

```
count = 0

while True:
    num = int(input("Enter number: "))

    if num == 0:
        break

    if num > 0:
        count += 1

print("Positive numbers =", count)
```

### Output

```
Enter number: 5
Enter number: -2
Enter number: 10
Enter number: 0
Positive numbers = 2
```

---

## Q30. Count the number of even and odd numbers between 1 and N.

### Code

```
n = int(input("Enter N: "))

even = 0
odd = 0

for i in range(1, n + 1):
    if i % 2 == 0:
        even += 1
    else:
        odd += 1

print("Even =", even)
print("Odd =", odd)
```

### Output

```
Enter N: 10
Even = 5
Odd = 5
```

---
## Q31. Display all factors of a given number.

### Code

```
num = int(input("Enter a number: "))

print("Factors are:")
for i in range(1, num + 1):
    if num % i == 0:
        print(i)
```

### Output

```
Enter a number: 12
Factors are:
1
2
3
4
6
12
```

---

## Q32. Check whether a given number is prime.

### Code

```
num = int(input("Enter a number: "))

prime = True

if num <= 1:
    prime = False
else:
    for i in range(2, num):
        if num % i == 0:
            prime = False
            break

if prime:
    print("Prime Number")
else:
    print("Not a Prime Number")
```

### Output

```
Enter a number: 13
Prime Number
```

---

## Q33. Find the factorial of a given number.

### Code

```
num = int(input("Enter a number: "))

fact = 1

for i in range(1, num + 1):
    fact *= i

print("Factorial =", fact)
```

### Output

```
Enter a number: 5
Factorial = 120
```

---

## Q34. Accept N numbers from the user and find the largest among them.

### Code

```
n = int(input("How many numbers? "))

largest = int(input("Enter number: "))

for i in range(n - 1):
    num = int(input("Enter number: "))
    if num > largest:
        largest = num

print("Largest number =", largest)
```

### Output

```
How many numbers? 5
Enter number: 10
Enter number: 25
Enter number: 18
Enter number: 30
Enter number: 12
Largest number = 30
```

---

## Q35. Keep accepting user input until the word "exit" is entered.

### Code

```
while True:
    text = input("Enter text: ")

    if text == "exit":
        break

print("Program Ended")
```

### Output

```
Enter text: Hello
Enter text: Python
Enter text: exit
Program Ended
```

---

## Q36. Print numbers from 1 to 50 but skip all multiples of 3.

### Code

```
for i in range(1, 51):
    if i % 3 == 0:
        continue
    print(i)
```

### Output

```
1
2
4
5
7
8
...
50
```

---

## Q37. Create an ATM PIN verification system.

### Code

```
correct_pin = "1234"

for attempt in range(3):
    pin = input("Enter PIN: ")

    if pin == correct_pin:
        print("Login Successful")
        break
else:
    print("Card Blocked")
```

### Output

```
Enter PIN: 1111
Enter PIN: 2222
Enter PIN: 1234
Login Successful
```

### Failed Output

```
Enter PIN: 1111
Enter PIN: 2222
Enter PIN: 3333
Card Blocked
```

---

## Q38. Create a Number Guessing Game.

### Code

```
secret = 25

while True:
    guess = int(input("Guess the number: "))

    if guess == secret:
        print("Correct Guess!")
        break
    else:
        print("Try Again")
```

### Output

```
Guess the number: 10
Try Again
Guess the number: 20
Try Again
Guess the number: 25
Correct Guess!
```

---

## Q39. Create a Student Result Analyzer.

### Code

```
highest = 0
lowest = 100
total = 0
passed = 0

for i in range(10):
    marks = int(input("Enter marks: "))

    if marks > highest:
        highest = marks

    if marks < lowest:
        lowest = marks

    total += marks

    if marks >= 40:
        passed += 1

average = total / 10

print("Highest Marks =", highest)
print("Lowest Marks =", lowest)
print("Average Marks =", average)
print("Passed Students =", passed)
```

### Output

```
Highest Marks = 95
Lowest Marks = 35
Average Marks = 68.5
Passed Students = 8
```

---

## Q40. Create a Mini Attendance System.

### Code

```
present = 0
absent = 0

for i in range(30):
    status = input("Present/Absent: ")

    if status.lower() == "present":
        present += 1
    else:
        absent += 1

percentage = (present / 30) * 100

print("Total Present =", present)
print("Total Absent =", absent)
print("Attendance Percentage =", percentage)
```

### Output

```
Total Present = 25
Total Absent = 5
Attendance Percentage = 83.33
```

---

## Q41. Accept N numbers one by one and display the running sum after every input.

### Code

```
n = int(input("Enter N: "))

total = 0

for i in range(n):
    num = int(input("Enter number: "))
    total += num
    print("Running Sum =", total)
```

### Output

```
Enter N: 4
Enter number: 5
Running Sum = 5
Enter number: 10
Running Sum = 15
Enter number: 2
Running Sum = 17
Enter number: 3
Running Sum = 20
```

---

## Q42. Print numbers from 1 to N using FizzBuzz rules.

### Code

```
n = int(input("Enter N: "))

for i in range(1, n + 1):
    if i % 3 == 0 and i % 5 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```

### Output

```
Enter N: 15

1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

---

## Q43. Check whether a given number is a palindrome number.

### Code

```
num = int(input("Enter a number: "))

original = num
reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num //= 10

if original == reverse:
    print("Palindrome")
else:
    print("Not Palindrome")
```

### Output

```
Enter a number: 121
Palindrome
```

### Output

```
Enter a number: 123
Not Palindrome
```

---

## Q44. Calculate xⁿ using loops only.

### Code

```
x = int(input("Enter base: "))
n = int(input("Enter exponent: "))

result = 1

for i in range(n):
    result *= x

print("Answer =", result)
```

### Output

```
Enter base: 2
Enter exponent: 5
Answer = 32
```

---

## Q45. Accept a number N and count how many prime numbers exist between 1 and N.

### Code

```
n = int(input("Enter N: "))

count = 0

for num in range(2, n + 1):
    prime = True

    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            prime = False
            break

    if prime:
        count += 1

print("Total Prime Numbers =", count)
```

### Output

```
Enter N: 20
Total Prime Numbers = 8
```

---
