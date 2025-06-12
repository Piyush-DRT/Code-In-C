# While Loop Practice – 20 Programming Questions

Organized into 4 categories of increasing difficulty. All questions use the **while loop** construct in C++.

---

## ✅ Category 1: Output Prediction (GATE Level)

**1.**
```cpp
int i = 1;
while (i <= 5) {
    cout << i << " ";
    i++;
}
2.

cpp
Copy
Edit
int i = 5;
while (i > 0) {
    cout << i-- << " ";
}
3.

cpp
Copy
Edit
int i = 1;
while (i < 10) {
    if (i % 3 == 0) break;
    cout << i << " ";
    i += 2;
}
4.

cpp
Copy
Edit
int i = 0;
while (i++ < 3) {
    cout << i << " ";
}
5.

cpp
Copy
Edit
int x = 2, count = 0;
while (x <= 100) {
    x = x * 2;
    count++;
}
cout << count;

🟨 Category 2: Basic Programming with While Loop
6. Sum of first N natural numbers (input: int N)

7. Count digits in a number (input: int n)

8. Reverse a given number (input: int n)

9. Check if a number is a palindrome (input: int n)

10. Find the factorial of a number using while loop (input: int n)

🟧 Category 3: Intermediate Problems (Logic + Conditions)
11. Count the number of 1s in the binary representation of a number (input: int n)

12. Find the sum of digits of a number until it becomes a single-digit number

13. Print all prime numbers up to N using only while loops (no arrays)

14. Find the GCD of two numbers using subtraction-based Euclidean algorithm

15. Convert a decimal number to binary (input: int n) and print it (without using arrays)

🟥 Category 4: DSA-Focused Challenges (High Thinking)
16. Given a number n, determine if it's a power of 2 using only while loop

17. Find the smallest digit in a number that is divisible by 3

18. Print the sum of alternate digits in a number (e.g., 12345 → 1+3+5)

19. Given a number n, return how many steps it takes to reduce it to 1 using:

If even: divide by 2

If odd: subtract 1

20. Print the binary equivalent of a number in reverse (e.g., 5 → binary 101 → print 101)
