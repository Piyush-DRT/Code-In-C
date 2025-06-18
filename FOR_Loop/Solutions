# ✅ FOR Loop Practice Solutions

Solutions and output explanations for all 40 FOR-loop-based problems categorized into increasing difficulty levels.

---

## 🟢 Category 1: Output-Based Questions

**1.** Output: `01 23 45`
**2.** Output: `35`
**3.** Output: `120`
**4.** Output: `00 11 22`
**5.** Output: `0123`
**6.** Output: `1 2 4`
**7.** Output: `1 3 5`
**8.**
```
***
**
*
```
**9.** Output: `6`
**10.** Output: `1 2 3 4 5 6 7 8 9 10`

---

## 🟡 Category 2: Beginner Logic – FOR Loops

**11.**
```cpp
int sum = 0;
for (int i = 1; i <= n; i++) sum += i * i;
cout << sum;
```

**12.**
```cpp
for (int i = 2; i <= n; i++) {
    if (n % i == 0) {
        cout << i;
        break;
    }
}
```

**13.**
```cpp
for (int i = 2; i <= n; i++) {
    bool isPrime = true;
    for (int j = 2; j * j <= i; j++)
        if (i % j == 0) isPrime = false;
    if (isPrime) cout << i << " ";
}
```

**14.**
```cpp
int count = 0;
for (int i = 1; i <= n; i++)
    if (i % 3 == 0 && i % 5 != 0) count++;
cout << count;
```

**15.**
```cpp
int rev = 0;
for (; n > 0; n /= 10) rev = rev * 10 + n % 10;
cout << rev;
```

**16.** Same as above, compare original with reverse.

**17.**
```cpp
int sum = 0;
for (int i = 1; i <= n; i++)
    sum += (i % 2 == 0) ? -i : i;
cout << sum;
```

**18.**
```cpp
int fact = 1;
for (int i = 1; i <= n; i++) fact *= i;
cout << fact;
```

**19.**
```cpp
for (int i = 10; i >= 1; i--) cout << n * i << " ";
```

**20.**
```cpp
int count = 0;
for (; n > 0; n /= 10) count++;
cout << count;
```

---

## 🟠 Category 3: Pattern Printing

**21.**
```cpp
for (int i = 1; i <= 4; i++) {
    for (int j = 1; j <= i; j++) cout << j;
    cout << "\n";
}
```

**22.**
```cpp
for (int i = 1; i <= 4; i++) {
    for (int j = 1; j <= 4 - i; j++) cout << ' ';
    for (int j = 1; j <= i; j++) cout << '*';
    cout << "\n";
}
```

**23.**
```cpp
for (int i = 1; i <= 4; i++) {
    for (int j = 1; j <= i; j++) cout << i;
    cout << "\n";
}
```

**24.**
```cpp
for (int i = 1; i <= 4; i++) {
    for (int j = i; j < 4; j++) cout << " ";
    for (char ch = 'A'; ch < 'A' + i; ch++) cout << ch;
    for (char ch = 'A' + i - 2; ch >= 'A'; ch--) cout << ch;
    cout << "\n";
}
```

**25.**
```cpp
for (int i = 0; i < 5; i++) {
    for (int j = 0; j < i; j++) cout << ' ';
    for (int j = 0; j < 5 - i; j++) cout << "* ";
    cout << "\n";
}
```

**26.** Fibonacci triangle – generate values, print till count < rowCount.

**27.** Pascal’s triangle – use nCr formula.

**28.**
```cpp
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        if (i == 0 || i == n - 1 || j == 0 || j == n - 1)
            cout << "*";
        else cout << " ";
    }
    cout << "\n";
}
```

**29.** Diagonal `\` only:
```cpp
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        if (i == j) cout << "*";
        else cout << " ";
    }
    cout << "\n";
}
```

**30.** Cross pattern:
```cpp
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        if (i == j || j == n - i - 1) cout << '*';
        else cout << ' ';
    }
    cout << "\n";
}
```

---

## 🔴 Category 4: DSA / GATE Level

**31.** Brute-force GCD:
```cpp
int gcd = 1;
for (int i = 1; i <= a && i <= b; i++)
    if (a % i == 0 && b % i == 0) gcd = i;
cout << gcd;
```

**32.** Distinct digits:
```cpp
bool seen[10] = {0};
for (; n > 0; n /= 10) seen[n % 10] = true;
int count = 0;
for (int i = 0; i < 10; i++) if (seen[i]) count++;
cout << count;
```

**33.** Second largest:
```cpp
int max1 = INT_MIN, max2 = INT_MIN;
for (int i = 0; i < n; i++) {
    if (arr[i] > max1) {
        max2 = max1;
        max1 = arr[i];
    } else if (arr[i] > max2 && arr[i] != max1) max2 = arr[i];
}
cout << max2;
```

**34.** Find duplicate:
```cpp
for (int i = 0; i < n; i++) {
    for (int j = i + 1; j < n; j++) {
        if (arr[i] == arr[j]) {
            cout << "Duplicate found: " << arr[i];
            return;
        }
    }
}
```

**35.** Power a^b:
```cpp
int result = 1;
for (int i = 1; i <= b; i++) result *= a;
cout << result;
```

**36.** Reverse array:
```cpp
for (int i = 0; i < n / 2; i++) swap(arr[i], arr[n - i - 1]);
```

**37.** Merge two sorted arrays:
```cpp
int i = 0, j = 0;
while (i < n && j < m) {
    if (a[i] < b[j]) cout << a[i++] << " ";
    else cout << b[j++] << " ";
}
while (i < n) cout << a[i++] << " ";
while (j < m) cout << b[j++] << " ";
```

**38.** Frequency of digits:
```cpp
int freq[10] = {0};
for (; n > 0; n /= 10) freq[n % 10]++;
for (int i = 0; i < 10; i++) cout << i << ": " << freq[i] << "\n";
```

**39.** Max product of consecutive:
```cpp
int maxProd = INT_MIN;
for (int i = 0; i < n - 1; i++) maxProd = max(maxProd, arr[i] * arr[i+1]);
cout << maxProd;
```

**40.** Check sorted:
```cpp
bool sorted = true;
for (int i = 1; i < n; i++) {
    if (arr[i] <= arr[i - 1]) sorted = false;
}
cout << (sorted ? "Yes" : "No");
