# 🚀 FOR LOOP Practice Set in C++

This document contains **FOR loop focused programming questions** split across 4 categories. Topics cover:
- **Output-based questions**
- **Basic logic building**
- **Pattern generation**
- **DSA logic-level with FOR loop control**

> 🎯 No repetition of previous WHILE loop questions. These are unique FOR-loop centric problems.

---

## 🟢 Category 1: Output-Based Questions (GATE Level)

**1.**
```cpp
for (int i = 0; i < 3; i++) {
    for (int j = 0; j <= i; j++)
        cout << i + j;
    cout << " ";
}
```

**2.**
```cpp
int sum = 0;
for (int i = 1; i <= 5; i++)
    sum += i * (6 - i);
cout << sum;
```

**3.**
```cpp
int fact = 1;
for (int i = 5; i >= 1; i--)
    fact *= i;
cout << fact;
```

**4.**
```cpp
int n = 3;
for (int i = 0; i < n; i++)
    for (int j = 0; j < n; j++)
        if (i == j)
            cout << i << j << " ";
```

**5.**
```cpp
for (int i = 0; i < 4; i++)
    for (int j = 0; j < 2; j++) {
        if (j == 1) break;
        cout << i;
    }
```

**6.**
```cpp
int x = 1;
for (int i = 0; i < 3; i++) {
    x = x + i;
    cout << x << " ";
}
```

**7.**
```cpp
for (int i = 1; i <= 5; i++) {
    if (i % 2 == 0) continue;
    cout << i << " ";
}
```

**8.**
```cpp
for (int i = 3; i > 0; i--) {
    for (int j = i; j > 0; j--)
        cout << "*";
    cout << "\n";
}
```

**9.**
```cpp
int a = 0;
for (int i = 0; i < 3; i++) {
    for (int j = 0; j <= i; j++)
        a++;
}
cout << a;
```

**10.**
```cpp
int k = 1;
for (int i = 1; i <= 4; i++)
    for (int j = 1; j <= i; j++)
        cout << k++ << " ";
```

---

## 🟡 Category 2: Beginner Logic – FOR Loops

**11.** Print the sum of squares from 1 to N.

**12.** Find the smallest divisor of N (greater than 1).

**13.** Print all prime numbers from 1 to N using for loop.

**14.** Count how many numbers from 1 to N are divisible by 3 but not by 5.

**15.** Reverse the digits of a number (use loop, no string conversion).

**16.** Check if a number is a palindrome using a for loop.

**17.** Compute the sum of alternate terms up to N (e.g., 1 - 2 + 3 - 4 + 5 ...).

**18.** Calculate factorial of a number using for loop.

**19.** Print the table of a number in reverse (from 10 to 1).

**20.** Count number of digits in a number.

---

## 🟠 Category 3: Pattern Printing (Logic Building)

**21.**
```
1
12
123
1234
```

**22.**
```
   *
  **
 ***
****
```

**23.**
```
1
22
333
4444
```

**24.**
```
   A
  ABA
 ABCBA
ABCDCBA
```

**25.**
```
* * * * *
 * * * *
  * * *
   * *
    *
```

**26.** Print Fibonacci triangle for N rows using FOR loop.

**27.** Pascal’s Triangle up to N rows.

**28.** Print hollow square of stars (size N).

**29.** Diagonal pattern:
```
*   
 *  
  * 
   *
```

**30.** Cross ‘X’ pattern with stars (odd N):
```
*   *
 * * 
  *  
 * * 
*   *
```

---

## 🔴 Category 4: DSA / GATE Level FOR Loop Practice

**31.** Implement GCD using brute-force method with FOR loop.

**32.** Count number of distinct digits in a number.

**33.** Write a program to find the second largest element in an array.

**34.** Find if any element appears more than once in an array (no extra space).

**35.** Calculate power `a^b` using loop only (no pow() function).

**36.** Reverse an array using a single FOR loop (in-place).

**37.** Merge two sorted arrays into a new sorted array (FOR-based merge logic).

**38.** Count frequency of each digit (0–9) in a given integer.

**39.** Find the maximum product of two consecutive elements in an array.

**40.** Check if array is sorted (strictly increasing) using FOR loop.
