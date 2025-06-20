# 🧩 C++ FOR Loop Practice Set – Focus on Patterns & Output

This set includes output-based and implementation-based pattern questions using FOR loops, progressing from basic to complex patterns.

---

## 🟢 Category 1 – Output Prediction (Trace & Predict Output)

1.
```cpp
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        cout << i << j << " ";
    }
    cout << endl;
}
```

2.
```cpp
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= i; j++) {
        cout << "*";
    }
    cout << endl;
}
```

3.
```cpp
for (int i = 3; i >= 1; i--) {
    for (int j = 1; j <= i; j++) {
        cout << j;
    }
    cout << endl;
}
```

4.
```cpp
int k = 1;
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= i; j++) {
        cout << k++ << " ";
    }
    cout << endl;
}
```

5.
```cpp
for (int i = 1; i <= 4; i++) {
    for (int j = 1; j <= i; j++) {
        cout << i;
    }
    cout << endl;
}
```

---

## 🟡 Category 2 – Basic Pattern Implementation

6. Print a right-angled triangle of stars of height N.

7. Print a triangle of numbers like:
```
1
1 2
1 2 3
```

8. Print an inverted triangle like:
```
* * *
* *
*
```

9. Print a number triangle like:
```
1
2 2
3 3 3
```

10. Print a square of size N using '*'.

---

## 🟠 Category 3 – Intermediate Pattern Programming

11. Print Pascal’s Triangle (first N rows).

12. Print half diamond pattern:
```
*
**
***
**
*
```

13. Print Floyd’s Triangle:
```
1
2 3
4 5 6
```

14. Print full pyramid of stars:
```
    *
   ***
  *****
```

15. Print numeric pyramid:
```
    1
   121
  12321
```

---

## 🔴 Category 4 – Advanced Pattern Logic

16. Print butterfly pattern:
```
*       *
**     **
***   ***
**** ****
*********
```

17. Print Z pattern for N:
```
****
   *
  *
****
```

18. Print hollow rectangle:
```
*****
*   *
*   *
*****
```

19. Print spiral numbers in square matrix (N x N).

20. Print diamond of numbers:
```
  1
 121
12321
 121
  1
```

---

✨ *This set is ideal for developing nested loop mastery, index control, symmetry logic, and output tracing confidence.*
