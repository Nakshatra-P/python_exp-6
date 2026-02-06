

## Aim:
To study and implement conditional statements in Python using `if`, `elif`, and `else` by solving multiple real-world programming problems involving numbers, grades, dates, salary, and tax calculations.

## Theory:
Conditional statements are used to make decisions in a program based on given conditions.  
Python provides `if`, `elif`, and `else` statements to evaluate expressions and execute corresponding blocks of code.  
These statements help control the flow of execution and are fundamental in solving logical problems such as comparisons, validations, and rule-based computations.

---

## Algorithms:

### 6a. Check Whether a Number is Positive, Negative, or Zero
1. Read an integer from the user.
2. If the number is greater than 0, print **Positive Number**.
3. Else if the number is less than 0, print **Negative Number**.
4. Otherwise, print **Number is Zero**.

---

### 6b. Check Whether a Number is Even or Odd
1. Read an integer from the user.
2. Check if the number modulo 2 equals 0.
3. If true, print **Even**.
4. Else, print **Odd**.

---

### 6c. Find the Largest of Three Numbers
1. Read three numbers from the user.
2. Compare the first number with the other two.
3. Compare the second number with the remaining number if required.
4. Print the largest number.

---

### 6d. Calculate Grade Based on Marks
1. Read marks from the user.
2. If marks ≥ 90, print **A Grade**.
3. Else if marks ≥ 75, print **B Grade**.
4. Else if marks ≥ 60, print **C Grade**.
5. Else if marks ≥ 40, print **D Grade**.
6. Otherwise, print **F Grade**.

---

### 6e. Calculate Average Marks and Grade for Three Subjects
1. Read marks of three subjects from the user.
2. Calculate the average.
3. Compare the average with grading criteria.
4. Display the average and corresponding grade.

---

### 6f. Check Whether a Year is a Leap Year
1. Read the year from the user.
2. If the year is divisible by 400, it is a leap year.
3. Else if divisible by 4 and not divisible by 100, it is a leap year.
4. Otherwise, it is not a leap year.
5. Display the result.

---

### 6g. Increment a Given Date
1. Read day, month, and year from the user.
2. Determine whether the year is a leap year.
3. Set the maximum days for the given month.
4. Increment the day by one.
5. If day exceeds maximum days, reset day to 1 and increment month.
6. If month exceeds 12, reset month to 1 and increment year.
7. Display the incremented date.

---

### 6h. Check Whether a Character is a Vowel or Consonant
1. Read a character from the user.
2. Check if the character belongs to the vowel set.
3. If true, print **Vowel**.
4. Else, print **Consonant**.

---

### 6i. Salary Calculation with Allowances
1. Read basic salary from the user.
2. If salary ≤ 10000, calculate HRA = 20% and DA = 80%.
3. Else if salary ≤ 20000, calculate HRA = 25% and DA = 90%.
4. Otherwise, calculate HRA = 30% and DA = 95%.
5. Add basic salary, HRA, and DA to get gross salary.
6. Display gross salary.

---

### 6j. Income Tax Calculation
1. Read annual income from the user.
2. If income ≤ 2,50,000, tax = 0.
3. If income is between 2,50,001 and 5,00,000, calculate 5% tax.
4. If income is between 5,00,001 and 10,00,000, calculate 20% tax on excess.
5. If income > 10,00,000, calculate 30% tax on excess.
6. Display payable income tax.

---

### 6k. Validate a Date and Print Incremented Date
1. Read date in `dd/mm/yyyy` format.
2. Extract day, month, and year.
3. Determine maximum days for the given month considering leap year.
4. Check if month and day are valid.
5. If invalid, print **Date is invalid**.
6. If valid, increment the date by one day.
7. Display the incremented date.

---

## Conclusion:
This experiment demonstrated the effective use of conditional statements in Python for solving various logical and real-life problems. By implementing multiple scenarios, a clear understanding of decision-making, comparisons, validations, and control flow was achieved. These concepts form the foundation for developing structured and reliable Python programs.
