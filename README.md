# Aim - Study While loop in Python

# Theory -
A while loop in Python is used to repeat a block of code as long as a condition is true.
It checks the condition first. If the condition is true, the loop runs. After each execution, it checks the condition again. When the condition becomes false, the loop stops.

# Algorithm - 
 i. Print i as long a i is less than 6:
   1. Start
   2. Initialize i = 0
   3. Check if i ≤ 5
   4. If true, print i
   5. Increase i by 1
   6. Repeat steps 3–5 until i > 5
   7. Stop

 ii. print n integer:
   1. Start
   2. Input the value of n
   3. Initialize i = 0
   4. Check if i ≤ n
   5. If true, print i
   6. Increase i by 1
   7. Repeat steps 4–6 until i > n
   8. Stop

 iii. Factorial of a number:
  1. Start
  2. Input the value of n
  3. Set fact = 1
  4. Check if n > 0
  5. If true, multiply fact by n
  6. Decrease n by 1
  7. Repeat steps 4–6 until n = 0
  8. Display fact as the factorial
  9. Stop
 
iv. Write a python program for a fibbonacci serise using while loop upto n terms
  1. Start
  2. Input the value of n (number of terms)
  3. Initialize i = 0, a = 0, b = 1
  4. Check if i ≤ n
  5. If true, print a
  6. Compute c = a + b
  7. Assign a = b
  8. Assign b = c
  9. Increase i by 1
  10. Repeat steps 4–9 until i > n
  11. Stop

v. Reverse a number:
  1. Start
  2. Input the value of n
  3. Initialize revnum = 0
  4. Check if n > 0
  5. If true, find the last digit: digit = n % 10
  6. Multiply revnum by 10
  7. Add digit to revnum
  8. Remove the last digit from n: n = n // 10
  9. Repeat steps 4–8 until n = 0
  10. Display revnum as the reversed number
  11. Stop

vi. Check Palindrome number:
  1. Start
  2. Define a function reverse(n)
  3. Inside the function, set revnum = 0
  4. While n > 0: Multiply revnum by 10, Add the last digit of n (n % 10) to revnum, Remove the last digit from n (n //= 10)
  5. Return revnum
  6. Input the number n
  7. Call reverse(n) and store the result
  8. Compare original n with reversed number
  9. If both are equal, print “Number is Palindrome”
  10. Otherwise, print “Number is Not a Palindrome”
  11. Stop

vii. Reverse a String:
  1. Start
  2. Input the string st
  3. Initialize revst = ""
  4. Set i = length of st
  5. While i > 0: Add character at position i-1 to revst, Decrease i by 1
  6. Compare st with revst
  7. If both are equal, print “String is Palindrome”
  8. Otherwise, print “String is Not a Palindrome”
  9. Stop

viii. Count Number of digits:
 1. Start
 2. Input the number num
 3. Initialize count = 0
 4. Check if num > 0
 5. If true, increase count by 1
 6. Remove the last digit of num using num = num // 10
 7. Repeat steps 4–6 until num = 0
 8. Display count as the total number of digits
 9. Stop

ix. Search an element in list using while loop:
 1. Start
 2. Initialize the list nums = [10, 20, 30, 40, 50]
 3. Input the value of key
 4. Set i = 0
 5. While i < length of list
 6. Check if nums[i] == key
 7. If true, print “Element found at index i” and stop the loop
 8. Otherwise, increase i by 1
 9. If loop completes without finding the element, print “Element not found”
 10. Stop

    
