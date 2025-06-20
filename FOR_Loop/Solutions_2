# ✅ C++ FOR Loop Programming Questions – Solutions

Solutions for the 4-level programming-based `for` loop practice set.

---

## 🟢 Category 1: Output-Based (Trace & Predict)

1. `1 2 3 4 5`

2. `25 16 9 4 1`

3.
```
1 
2 4 
3 6 9 
```

4.
```
2 
3 4 
4 5 6 
5 6 7 8 
```

5. `6` (2 + 4)

---

## 🟡 Category 2: Logic Building with FOR

6.
```cpp
for (int i = 2; i <= N; i += 2) cout << i << " ";
```

7.
```cpp
int count = 0;
for (; num != 0; num /= 10) count++;
```

8.
```cpp
int fact = 1;
for (int i = 1; i <= n; i++) fact *= i;
```

9.
```cpp
bool prime = true;
for (int i = 2; i < n; i++) {
    if (n % i == 0) prime = false;
}
```

10.
```cpp
int sum = 0;
for (int i = 1; i <= N; i++) sum += i * i;
```

11.
```cpp
int a = 0, b = 1;
for (int i = 0; i < N; i++) {
    cout << a << " ";
    int temp = a + b;
    a = b;
    b = temp;
}
```

12.
```cpp
int rev = 0;
for (; num != 0; num /= 10) rev = rev * 10 + num % 10;
```

13.
```cpp
int maxVal = a * b;
for (int i = max(a, b); i <= maxVal; i++) {
    if (i % a == 0 && i % b == 0) { cout << i; break; }
}
```

14.
```cpp
int count = 0;
for (; n != 0; n /= 10) {
    if ((n % 10) % 3 == 0) count++;
}
```

15.
```cpp
int sum = 0;
for (int i = 1; i < n; i++) {
    if (n % i == 0) sum += i;
}
cout << (sum == n ? "Perfect" : "Not perfect");
```

---

## 🟠 Category 3: Math & Pattern Logic

16.
```cpp
int count = 0;
for (int i = 2; count < N; i++) {
    bool prime = true;
    for (int j = 2; j < i; j++) {
        if (i % j == 0) { prime = false; break; }
    }
    if (prime) { cout << i << " "; count++; }
}
```

17.
```cpp
int gcd = 1;
for (int i = 1; i <= a && i <= b; i++) {
    if (a % i == 0 && b % i == 0) gcd = i;
}
```

18.
```cpp
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= i; j++) cout << i * j << " ";
    cout << endl;
}
```

19.
```cpp
for (int a = 1; a < 100; a++) {
    for (int b = a; b < 100; b++) {
        int c = sqrt(a*a + b*b);
        if (c*c == a*a + b*b && c < 100) cout << a << "," << b << "," << c << endl;
    }
}
```

20.
```cpp
for (int i = 1; i <= N; i++) {
    int sum = 0, temp = i;
    for (; temp > 0; temp /= 10) {
        int d = temp % 10;
        sum += d*d*d;
    }
    if (sum == i) cout << i << " ";
}
```

21.
```cpp
int decimal = 0, base = 1;
for (int temp = binary; temp > 0; temp /= 10) {
    int lastDigit = temp % 10;
    decimal += lastDigit * base;
    base *= 2;
}
```

22.
```cpp
int octal = 0, base = 1;
for (; n > 0; n /= 8) {
    octal += (n % 8) * base;
    base *= 10;
}
```

23.
```cpp
int result = 1;
for (int i = 1; i <= b; i++) result *= a;
```

24.
```cpp
int sum = 0;
for (int i = 1; i <= n; i++) {
    int fact = 1;
    for (int j = 1; j <= i; j++) fact *= j;
    sum += fact;
}
```

25.
```cpp
char ch = 'A';
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= i; j++) cout << ch << " ";
    ch++;
    cout << endl;
}
```

---

## 🔴 Category 4: DSA & Complex Logic

26.
```cpp
for (int i = 0; i < n; i++) {
    for (int j = i + 1; j < n; j++) {
        if (arr[i] == arr[j]) cout << arr[i] << " ";
    }
}
```

27.
```cpp
bool isPalin = true;
for (int i = 0; i < n / 2; i++) {
    if (arr[i] != arr[n - i - 1]) isPalin = false;
}
```

28.
```cpp
int freq[256] = {0};
for (int i = 0; s[i]; i++) freq[s[i]]++;
```

29.
```cpp
for (int i = 0; i < n; i++) {
    for (int j = i + 1; j < n; j++) {
        if (arr[i] + arr[j] == k) count++;
    }
}
```

30.
```cpp
int temp[k];
for (int i = 0; i < k; i++) temp[i] = arr[n - k + i];
for (int i = n - 1; i >= k; i--) arr[i] = arr[i - k];
for (int i = 0; i < k; i++) arr[i] = temp[i];
```

31.
```cpp
for (int i = 0; i < n; i++) {
    bool leader = true;
    for (int j = i + 1; j < n; j++) {
        if (arr[i] < arr[j]) { leader = false; break; }
    }
    if (leader) cout << arr[i] << " ";
}
```

32.
```cpp
int i = 0, j = 0;
for (; i < n1 && j < n2; ) {
    if (arr1[i] < arr2[j]) cout << arr1[i++] << " ";
    else cout << arr2[j++] << " ";
}
for (; i < n1; i++) cout << arr1[i] << " ";
for (; j < n2; j++) cout << arr2[j] << " ";
```

33.
```cpp
for (int i = 0; i < n1; i++) {
    for (int j = 0; j < n2; j++) {
        if (arr1[i] == arr2[j]) cout << arr1[i] << " ";
    }
}
```

34.
```cpp
int unique = 0;
for (int i = 0; i < n; i++) {
    bool found = false;
    for (int j = 0; j < i; j++) {
        if (arr[i] == arr[j]) { found = true; break; }
    }
    if (!found) unique++;
}
```

35.
```cpp
int freq[10] = {0};
for (int i = 0; i < n; i++) freq[arr[i]]++;
for (int i = 1; i <= 9; i++) {
    cout << i << ": ";
    for (int j = 0; j < freq[i]; j++) cout << "*";
    cout << endl;
}
```

---

✨ *Use these solutions to test, debug, and learn real-world logic built using simple `for` loops!*
