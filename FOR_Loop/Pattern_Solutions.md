# ✅ C++ FOR Loop Pattern Practice Set – Solutions

Below are the solutions or outputs for each of the 20 questions in the FOR loop pattern-based practice set.

---

## 🟢 Category 1 – Output Prediction

1.
```
11 12 13 
21 22 23 
31 32 33
```

2.
```
*
**
***
```

3.
```
123
12
1
```

4.
```
1 
2 3 
4 5 6
```

5.
```
1
22
333
4444
```

---

## 🟡 Category 2 – Basic Patterns

6.
```cpp
for(int i=1; i<=n; i++) {
    for(int j=1; j<=i; j++) cout << "*";
    cout << endl;
}
```

7.
```cpp
for(int i=1; i<=n; i++) {
    for(int j=1; j<=i; j++) cout << j << " ";
    cout << endl;
}
```

8.
```cpp
for(int i=n; i>=1; i--) {
    for(int j=1; j<=i; j++) cout << "* ";
    cout << endl;
}
```

9.
```cpp
for(int i=1; i<=n; i++) {
    for(int j=1; j<=i; j++) cout << i << " ";
    cout << endl;
}
```

10.
```cpp
for(int i=1; i<=n; i++) {
    for(int j=1; j<=n; j++) cout << "* ";
    cout << endl;
}
```

---

## 🟠 Category 3 – Intermediate Patterns

11.
```cpp
int coeff;
for(int i = 0; i < n; i++) {
    coeff = 1;
    for(int j = 0; j <= i; j++) {
        cout << coeff << " ";
        coeff = coeff * (i - j) / (j + 1);
    }
    cout << endl;
}
```

12.
```
*
**
***
**
*
```

13.
```cpp
int k = 1;
for(int i=1; i<=n; i++) {
    for(int j=1; j<=i; j++) cout << k++ << " ";
    cout << endl;
}
```

14.
```cpp
for(int i = 1; i <= n; i++) {
    for(int j = 1; j <= n - i; j++) cout << " ";
    for(int j = 1; j <= 2*i - 1; j++) cout << "*";
    cout << endl;
}
```

15.
```cpp
for(int i=1; i<=n; i++) {
    for(int j=1; j<=n-i; j++) cout << " ";
    for(int j=1; j<=i; j++) cout << j;
    for(int j=i-1; j>=1; j--) cout << j;
    cout << endl;
}
```

---

## 🔴 Category 4 – Advanced Pattern Logic

16.
```cpp
for(int i = 1; i <= n; i++) {
    for(int j = 1; j <= i; j++) cout << "*";
    for(int j = 1; j <= 2*(n-i); j++) cout << " ";
    for(int j = 1; j <= i; j++) cout << "*";
    cout << endl;
}
```

17.
```cpp
for(int i = 1; i <= n; i++) {
    for(int j = 1; j <= n; j++) {
        if(i == 1 || i == n || j == n - i + 1)
            cout << "*";
        else cout << " ";
    }
    cout << endl;
}
```

18.
```cpp
for(int i = 1; i <= r; i++) {
    for(int j = 1; j <= c; j++) {
        if(i == 1 || i == r || j == 1 || j == c) cout << "*";
        else cout << " ";
    }
    cout << endl;
}
```

19. Spiral printing involves layer-wise traversal of a matrix; best implemented with index tracking (`top`, `bottom`, `left`, `right`).

20.
```cpp
for(int i = 1; i <= n; i++) {
    for(int j = 1; j <= n - i; j++) cout << " ";
    for(int j = 1; j <= i; j++) cout << j;
    for(int j = i - 1; j >= 1; j--) cout << j;
    cout << endl;
}
for(int i = n-1; i >= 1; i--) {
    for(int j = 1; j <= n - i; j++) cout << " ";
    for(int j = 1; j <= i; j++) cout << j;
    for(int j = i - 1; j >= 1; j--) cout << j;
    cout << endl;
}
```

---

✨ *You can copy-paste and test each block individually to better understand nested loops and complex pattern structure.*
