# Increment/Decrement Practice – Questions with Solutions

---

## ✅ Category 1: Output Prediction

**1.**
```cpp
int i = 0;
cout << i++ << " " << ++i;
// Output: 0 2
```

**2.**
```cpp
int a = 5;
cout << ++a + a++;
// Output: 12
```

**3.**
```cpp
int x = 3, y = 4;
cout << x++ + ++y;
// Output: 3 + 5 = 8
```

**4.**
```cpp
int i = 1;
while (i++ < 3) {
    cout << i << " ";
}
// Output: 2 3
```

**5.**
```cpp
int a = 10;
int b = a++ + ++a + a--;
// 10 + 12 + 12 = 34
cout << b;
// Output: 34
```

---

## 🟨 Category 2: Basic Programming

**6.**
```cpp
int n, i = 1;
cin >> n;
while (i <= n) {
    cout << i << " ";
    i++;
}
```

**7.**
```cpp
int n;
cin >> n;
while (n >= 1) {
    cout << n << " ";
    n--;
}
```

**8.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    n /= 10;
    count++;
}
cout << count;
```

**9.**
```cpp
int n, rev = 0;
cin >> n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << rev;
```

**10.**
```cpp
char ch = 'A';
while (ch <= 'Z') {
    cout << ch << " : " << int(ch) << endl;
    ch++;
}
```

---

## 🟧 Category 3: Logic-Based

**11.**
```cpp
int n, sum = 0, i = 1;
cin >> n;
while (i <= n) {
    if (i % 2 != 0) sum += i;
    i++;
}
cout << sum;
```

**12.**
```cpp
int n, count = 0;
cin >> n;
while (n > 0) {
    if ((n % 10) % 2 == 0) count++;
    n /= 10;
}
cout << count;
```

**13.**
```cpp
int n;
cin >> n;
while (n > 0) {
    cout << n % 10 << " ";
    n /= 10;
}
```

**14.**
```cpp
char ch = 'a';
while (ch <= 'z') {
    cout << ch << " -> " << char(ch - 32) << endl;
    ch++;
}
```

**15.**
```cpp
int n, rev = 0, original;
cin >> n;
original = n;
while (n > 0) {
    rev = rev * 10 + n % 10;
    n /= 10;
}
cout << (rev == original ? "Palindrome" : "Not Palindrome");
```

---

## 🟥 Category 4: DSA Level

**16.**
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

**17.**
```cpp
int n, a = 0, b = 1, c, i = 1;
cin >> n;
cout << a << " " << b << " ";
while (i <= n - 2) {
    c = a + b;
    cout << c << " ";
    a = b;
    b = c;
    i++;
}
```

**18.**
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

**19.**
```cpp
string str;
cin >> str;
int i = 0, count = 0;
while (str[i] != '\0') {
    char ch = tolower(str[i]);
    if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
        count++;
    i++;
}
cout << count;
```

**20.**
```cpp
int n, fact = 1;
cin >> n;
while (n > 0) {
    fact *= n;
    n--;
}
cout << fact;
```
