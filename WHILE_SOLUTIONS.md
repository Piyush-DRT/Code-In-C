# While Loop Practice – Questions + Solutions

This file contains all 20 while-loop practice questions along with their C++ solutions.

---

## ✅ Category 1: Output Prediction (GATE Level)

**1.**
```cpp
int i = 1;
while (i <= 5) {
    cout << i << " ";
    i++;
}
// Output: 1 2 3 4 5
```

**2.**
```cpp
int i = 5;
while (i > 0) {
    cout << i-- << " ";
}
// Output: 5 4 3 2 1
```

**3.**
```cpp
int i = 1;
while (i < 10) {
    if (i % 3 == 0) break;
    cout << i << " ";
    i += 2;
}
// Output: 1
```

**4.**
```cpp
int i = 0;
while (i++ < 3) {
    cout << i << " ";
}
// Output: 1 2 3
```

**5.**
```cpp
int x = 2, count = 0;
while (x <= 100) {
    x = x * 2;
    count++;
}
cout << count;
// Output: 6
```

---

## 🟨 Category 2: Basic Programming with While Loop

**6.**
```cpp
int n, sum = 0;
cin >> n;
while (n > 0) {
    sum += n;
    n--;
}
cout << sum;
```

**7.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    count++;
    n /= 10;
}
cout << count;
```

**8.**
```cpp
int n, rev = 0;
cin >> n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << rev;
```

**9.**
```cpp
int n, rev = 0, temp;
cin >> n;
temp = n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << (rev == temp ? "Palindrome" : "Not Palindrome");
```

**10.**
```cpp
int n, fact = 1;
cin >> n;
while (n > 0) {
    fact *= n;
    n--;
}
cout << fact;
```

---

## 🟧 Category 3: Intermediate Problems

**11.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    count += n % 2;
    n /= 2;
}
cout << count;
```

**12.**
```cpp
int n, sum;
cin >> n;
while (n >= 10) {
    sum = 0;
    while (n > 0) {
        sum += n % 10;
        n /= 10;
    }
    n = sum;
}
cout << n;
```

**13.**
```cpp
int n, i = 2;
cin >> n;
while (i <= n) {
    int j = 2, flag = 1;
    while (j * j <= i) {
        if (i % j == 0) {
            flag = 0;
            break;
        }
        j++;
    }
    if (flag) cout << i << " ";
    i++;
}
```

**14.**
```cpp
int a, b;
cin >> a >> b;
while (a != b) {
    if (a > b) a = a - b;
    else b = b - a;
}
cout << a;
```

**15.**
```cpp
int n;
cin >> n;
while (n > 0) {
    cout << (n % 2);
    n /= 2;
}
```

---

## 🟥 Category 4: DSA-Focused Challenges

**16.**
```cpp
int n;
cin >> n;
bool isPower = true;
if (n <= 0) isPower = false;
while (n > 1) {
    if (n % 2 != 0) {
        isPower = false;
        break;
    }
    n /= 2;
}
cout << (isPower ? "Yes" : "No");
```

**17.**
```cpp
int n, minDigit = 10;
cin >> n;
while (n > 0) {
    int d = n % 10;
    if (d % 3 == 0 && d < minDigit) minDigit = d;
    n /= 10;
}
if (minDigit < 10) cout << minDigit;
else cout << "None";
```

**18.**
```cpp
int n, sum = 0, pos = 1;
cin >> n;
while (n > 0) {
    if (pos % 2 == 1) sum += n % 10;
    n /= 10;
    pos++;
}
cout << sum;
```

**19.**
```cpp
int n, steps = 0;
cin >> n;
while (n > 1) {
    if (n % 2 == 0) n /= 2;
    else n -= 1;
    steps++;
}
cout << steps;
```

**20.**
```cpp
int n;
cin >> n;
while (n > 0) {
    cout << (n % 2);
    n /= 2;
}
```
# While Loop Practice – Questions + Solutions

This file contains all 20 while-loop practice questions along with their C++ solutions.

---

## ✅ Category 1: Output Prediction (GATE Level)

**1.**
```cpp
int i = 1;
while (i <= 5) {
    cout << i << " ";
    i++;
}
// Output: 1 2 3 4 5
```

**2.**
```cpp
int i = 5;
while (i > 0) {
    cout << i-- << " ";
}
// Output: 5 4 3 2 1
```

**3.**
```cpp
int i = 1;
while (i < 10) {
    if (i % 3 == 0) break;
    cout << i << " ";
    i += 2;
}
// Output: 1
```

**4.**
```cpp
int i = 0;
while (i++ < 3) {
    cout << i << " ";
}
// Output: 1 2 3
```

**5.**
```cpp
int x = 2, count = 0;
while (x <= 100) {
    x = x * 2;
    count++;
}
cout << count;
// Output: 6
```

---

## 🟨 Category 2: Basic Programming with While Loop

**6.**
```cpp
int n, sum = 0;
cin >> n;
while (n > 0) {
    sum += n;
    n--;
}
cout << sum;
```

**7.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    count++;
    n /= 10;
}
cout << count;
```

**8.**
```cpp
int n, rev = 0;
cin >> n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << rev;
```

**9.**
```cpp
int n, rev = 0, temp;
cin >> n;
temp = n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << (rev == temp ? "Palindrome" : "Not Palindrome");
```

**10.**
```cpp
int n, fact = 1;
cin >> n;
while (n > 0) {
    fact *= n;
    n--;
}
cout << fact;
```

---

## 🟧 Category 3: Intermediate Problems

**11.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    count += n % 2;
    n /= 2;
}
cout << count;
```

**12.**
```cpp
int n, sum;
cin >> n;
while (n >= 10) {
    sum = 0;
    while (n > 0) {
        sum += n % 10;
        n /= 10;
    }
    n = sum;
}
cout << n;
```

**13.**
```cpp
int n, i = 2;
cin >> n;
while (i <= n) {
    int j = 2, flag = 1;
    while (j * j <= i) {
        if (i % j == 0) {
            flag = 0;
            break;
        }
        j++;
    }
    if (flag) cout << i << " ";
    i++;
}
```

**14.**
```cpp
int a, b;
cin >> a >> b;
while (a != b) {
    if (a > b) a = a - b;
    else b = b - a;
}
cout << a;
```

**15.**
```cpp
int n;
cin >> n;
while (n > 0) {
    cout << (n % 2);
    n /= 2;
}
```

---

## 🟥 Category 4: DSA-Focused Challenges

**16.**
```cpp
int n;
cin >> n;
bool isPower = true;
if (n <= 0) isPower = false;
while (n > 1) {
    if (n % 2 != 0) {
        isPower = false;
        break;
    }
    n /= 2;
}
cout << (isPower ? "Yes" : "No");
```

**17.**
```cpp
int n, minDigit = 10;
cin >> n;
while (n > 0) {
    int d = n % 10;
    if (d % 3 == 0 && d < minDigit) minDigit = d;
    n /= 10;
}
if (minDigit < 10) cout << minDigit;
else cout << "None";
```

**18.**
```cpp
int n, sum = 0, pos = 1;
cin >> n;
while (n > 0) {
    if (pos % 2 == 1) sum += n % 10;
    n /= 10;
    pos++;
}
cout << sum;
```

**19.**
```cpp
int n, steps = 0;
cin >> n;
while (n > 1) {
    if (n % 2 == 0) n /= 2;
    else n -= 1;
    steps++;
}
cout << steps;
```

**20.**
```cpp
int n;
cin >> n;
while (n > 0) {
    cout << (n % 2);
    n /= 2;
}
```
