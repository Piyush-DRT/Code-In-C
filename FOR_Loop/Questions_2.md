# 🔁 C++ FOR Loop Programming Questions – Practice Set

This set includes logic-building and DSA-oriented problems using `for` loops. Divided into 4 levels, from basic to challenging.

---

## 🟢 Category 1: Output-Based (Trace & Predict)

1.
```cpp
for(int i=1; i<=5; i++) {
    cout << i << " ";
}
```

2.
```cpp
for(int i=5; i>=1; i--) {
    cout << i*i << " ";
}
```

3.
```cpp
for(int i=1; i<=3; i++) {
    for(int j=1; j<=i; j++) {
        cout << i*j << " ";
    }
    cout << endl;
}
```

4.
```cpp
for(int i=1; i<=4; i++) {
    for(int j=1; j<=i; j++) cout << i+j << " ";
    cout << endl;
}
```

5.
```cpp
int sum = 0;
for(int i=1; i<=5; i++) {
    if(i % 2 == 0) sum += i;
}
cout << sum;
```

---

## 🟡 Category 2: Logic Building with FOR

6. Print all even numbers from 1 to N.

7. Count digits in a given number using a `for` loop.

8. Print factorial of a given number.

9. Check if a number is prime.

10. Find sum of squares of first N natural numbers.

11. Print Fibonacci sequence up to N terms using `for` loop.

12. Reverse a number using `for` loop.

13. Find LCM of two numbers using `for` loop.

14. Count number of digits divisible by 3 in a number.

15. Check if a number is a perfect number.

---

## 🟠 Category 3: Math & Patterns with Logic

16. Generate first N prime numbers using `for`.

17. Find GCD using `for` loop.

18. Print a pattern of multiples like:
```
1
2 4
3 6 9
```

19. Generate all Pythagorean triplets below 100.

20. Print Armstrong numbers from 1 to N.

21. Convert binary to decimal using `for` loop.

22. Convert decimal to octal using `for` loop.

23. Find power of number using loop (A^B).

24. Print sum of factorials from 1 to N.

25. Print pattern:
```
A
B B
C C C
```

---

## 🔴 Category 4: DSA & Complex Logic

26. Find duplicate elements in an array.

27. Check if array is palindrome.

28. Print frequency of each character in a string using loop.

29. Count pairs in an array whose sum is equal to a given K.

30. Rotate array to the right by K steps using `for` loop.

31. Find the leader elements in an array (greater than all to its right).

32. Merge two sorted arrays using only loops.

33. Find intersection of two arrays using `for` loop.

34. Count unique elements in array using only loops.

35. Create frequency histogram of integers from 1–9 in an array using `for`.

---

✨ *This set emphasizes logical, mathematical, and DSA readiness using just the power of `for` loops.*
