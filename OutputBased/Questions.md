# 🚀 C++ Practice Set: Scope, Global Variables, Increment/Decrement, Operators & Reference Variables

This document contains **output-based and logic-oriented questions** in 4 progressive levels. Each category combines topics:
- **Scope (local/global)**
- **Pre/Post Increment & Decrement**
- **Operators (arithmetic, logical, bitwise)**
- **Reference Variables**

---

## 🟢 Category 1: Basics Combined (Level 1)

**1.**
```cpp
int a = 5;
int &ref = a;
ref++;
cout << a;
```

**2.**
```cpp
int a = 10;
{
    int a = 20;
    cout << a << " ";
}
cout << a;
```

**3.**
```cpp
int a = 3;
int b = a++ + ++a;
cout << a << " " << b;
```

**4.**
```cpp
int a = 5;
int &r = a;
r += 10;
cout << a << " " << r;
```

**5.**
```cpp
int x = 1;
if (x++ == 1 && ++x == 3)
    cout << x;
else
    cout << x * 2;
```

**6.**
```cpp
int a = 4, b = 5;
b = a++ + ++b;
cout << a << " " << b;
```

**7.**
```cpp
int val = 1;
{
    int val = 2;
    cout << ++val << " ";
}
cout << val;
```

**8.**
```cpp
int a = 10;
int *p = &a;
(*p)++;
cout << a;
```

**9.**
```cpp
int a = 3;
a = a++ + a++;
cout << a;
```

**10.**
```cpp
int a = 1;
int &ref = a;
ref = ref++;
cout << ref;
```

---

## 🟡 Category 2: Intermediate Logic (Level 2)

**11.**
```cpp
int x = 5;
int y = x++ + x++ + ++x;
cout << x << " " << y;
```

**12.**
```cpp
int a = 1;
if (++a == 2 || a++ == 3)
    cout << a;
```

**13.**
```cpp
int x = 2;
int &r = x;
r = r++ + ++x;
cout << r;
```

**14.**
```cpp
int a = 5;
{
    int a = a + 1; // undefined behavior
    cout << a;
}
```

**15.**
```cpp
int x = 10;
int &ref = x;
ref = ref++ * 2;
cout << x;
```

**16.**
```cpp
int a = 1, b = 2;
int &r = a;
r = b;
b++;
cout << a << " " << b;
```

**17.**
```cpp
int a = 5;
int b = a++ * 2 + ++a;
cout << a << " " << b;
```

**18.**
```cpp
int a = 5;
int b = a++ + a++ + a++;
cout << b;
```

**19.**
```cpp
int a = 2;
int b = a++ * ++a;
cout << b;
```

**20.**
```cpp
int x = 3;
{
    int &r = x;
    r++;
}
cout << x;
```

---

## 🟠 Category 3: Advanced Expressions (Level 3)

**21.**
```cpp
int a = 3;
int b = 4;
int c = a++ + ++b * ++a;
cout << c;
```

**22.**
```cpp
int x = 10;
int y = x++ + x++ + ++x + x;
cout << y;
```

**23.**
```cpp
int a = 1;
int &r = a;
int b = ++r + r++ + r;
cout << b;
```

**24.**
```cpp
int val = 2;
int &r = val;
r = ++r + r++;
cout << val;
```

**25.**
```cpp
int x = 1;
int &r1 = x;
int &r2 = r1;
r2++;
cout << x;
```

**26.**
```cpp
int a = 4;
int b = 5;
int &ref = a;
ref = b;
ref++;
cout << a << " " << b;
```

**27.**
```cpp
int a = 10;
{
    int b = a++ + ++a + a;
    cout << b;
}
```

**28.**
```cpp
int x = 5;
int y = ++x * x++ + ++x;
cout << x << " " << y;
```

**29.**
```cpp
int x = 0;
if (x++ && ++x)
    cout << x;
else
    cout << x * 2;
```

**30.**
```cpp
int a = 7;
int &ref = a;
ref = ref++ + ++ref;
cout << a;
```

---

## 🔴 Category 4: GATE/DSA Logic-Level (Level 4)

**31.**
```cpp
int global = 10;
void fun() {
    global++;
    cout << global;
}
int main() {
    fun();
    cout << global;
}
```

**32.**
```cpp
int a = 3;
int &r = a;
int b = a++ + ++r + r++;
cout << a << " " << b;
```

**33.**
```cpp
int f(int &x) {
    x++;
    return x;
}
int main() {
    int a = 5;
    int b = f(a);
    cout << a << " " << b;
}
```

**34.**
```cpp
int x = 3;
int y = (x++ * x++); 
cout << y;
```

**35.**
```cpp
int a = 2;
int &r1 = a;
int &r2 = r1;
r2 = ++r1 + r2++;
cout << a;
```

**36.**
```cpp
int count = 0;
for (int i = 0; i < 3; i++) {
    for (int j = 0; j < i; j++) {
        count++;
    }
}
cout << count;
```

**37.**
```cpp
int a = 5;
int b = 6;
int &r = a;
r = b;
cout << a << " " << b;
```

**38.**
```cpp
int a = 1;
int b = ++a * ++a;
cout << a << " " << b;
```

**39.**
```cpp
int x = 2;
int y = x++ * x++ * x++;
cout << x << " " << y;
```

**40.**
```cpp
int a = 4;
int &r = a;
int x = r++ * ++r;
cout << x << " " << a;
```
```

