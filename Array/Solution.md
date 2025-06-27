# ✅ C++ Arrays – Solutions to Practice Problems

Solutions and outputs for the 4-level C++ Array questions.

---

## 🟢 Category 1: Output-Based Questions

1. `10 20 30 40`

2. `5 4 3 2 1`

3. `10 15 20`

4. `1 0 0 0 0` (only first element initialized to 1)

5. `12` (4 + 8)

---

## 🟡 Category 2: Basic Array Operations

6.
```cpp
for(int i = N - 1; i >= 0; i--) cout << arr[i] << " ";
```

7.
```cpp
int max = arr[0], min = arr[0];
for(int i = 1; i < n; i++) {
    if(arr[i] > max) max = arr[i];
    if(arr[i] < min) min = arr[i];
}
```

8.
```cpp
int even = 0, odd = 0;
for(int i = 0; i < n; i++) {
    if(arr[i] % 2 == 0) even++;
    else odd++;
}
```

9.
```cpp
int sum = 0;
for(int i = 0; i < n; i++) sum += arr[i];
double avg = (double)sum / n;
```

10.
```cpp
int first = INT_MIN, second = INT_MIN;
for(int i = 0; i < n; i++) {
    if(arr[i] > first) {
        second = first;
        first = arr[i];
    } else if(arr[i] > second && arr[i] != first) second = arr[i];
}
```

11.
```cpp
for(int i = 0; i < n; i++) if(arr[i] == x) return i;
```

12.
```cpp
for(int i = n; i > index; i--) arr[i] = arr[i-1];
arr[index] = value;
```

13.
```cpp
for(int i = index; i < n - 1; i++) arr[i] = arr[i+1];
```

14.
```cpp
for(int i = 0; i < n; i++) arr2[i] = arr1[i];
```

15.
```cpp
int count = 0;
for(int i = 0; i < n; i++) if(arr[i] == x) count++;
```

---

## 🟠 Category 3: Logic Building

16.
```cpp
bool sorted = true;
for(int i = 0; i < n - 1; i++) {
    if(arr[i] > arr[i+1]) { sorted = false; break; }
}
```

17.
```cpp
bool palin = true;
for(int i = 0; i < n / 2; i++) if(arr[i] != arr[n - i - 1]) palin = false;
```

18.
```cpp
for(int i = 0; i < n; i++) {
    for(int j = i + 1; j < n; j++) {
        if(arr[i] == arr[j]) cout << arr[i] << " ";
    }
}
```

19.
```cpp
int merged[n1 + n2];
for(int i = 0; i < n1; i++) merged[i] = arr1[i];
for(int i = 0; i < n2; i++) merged[n1 + i] = arr2[i];
```

20.
```cpp
int pos = 0;
for(int i = 0; i < n; i++) {
    if(arr[i] != 0) arr[pos++] = arr[i];
}
while(pos < n) arr[pos++] = 0;
```

21.
```cpp
int maxCount = 0, freqElement;
for(int i = 0; i < n; i++) {
    int count = 0;
    for(int j = 0; j < n; j++) if(arr[i] == arr[j]) count++;
    if(count > maxCount) {
        maxCount = count;
        freqElement = arr[i];
    }
}
```

22.
```cpp
int unique = 0;
for(int i = 0; i < n; i++) {
    bool isDuplicate = false;
    for(int j = 0; j < i; j++) if(arr[i] == arr[j]) isDuplicate = true;
    if(!isDuplicate) unique++;
}
```

23.
```cpp
int temp[n], k = 0;
for(int i = 0; i < n; i++) {
    bool exists = false;
    for(int j = 0; j < k; j++) if(arr[i] == temp[j]) exists = true;
    if(!exists) temp[k++] = arr[i];
}
```

24.
```cpp
int evenSum = 0, oddSum = 0;
for(int i = 0; i < n; i++) {
    if(i % 2 == 0) evenSum += arr[i];
    else oddSum += arr[i];
}
```

25.
```cpp
for(int i = 0; i < n; i++) if(arr[i] < 0) arr[i] = 0;
```

---

## 🔴 Category 4: DSA-Level Solutions

26.
```cpp
for(int i = 0; i < n; i++) {
    bool leader = true;
    for(int j = i + 1; j < n; j++) {
        if(arr[i] <= arr[j]) { leader = false; break; }
    }
    if(leader) cout << arr[i] << " ";
}
```

27.
```cpp
int temp[k];
for(int i = 0; i < k; i++) temp[i] = arr[n - k + i];
for(int i = n - 1; i >= k; i--) arr[i] = arr[i - k];
for(int i = 0; i < k; i++) arr[i] = temp[i];
```

28.
```cpp
int count = 0;
for(int i = 0; i < n; i++) {
    for(int j = i + 1; j < n; j++) {
        if(arr[i] + arr[j] == k) count++;
    }
}
```

29.
```cpp
int low = 0, high = n - 1;
while(low <= high) {
    int mid = (low + high) / 2;
    if(arr[mid] == x) return mid;
    else if(arr[mid] < x) low = mid + 1;
    else high = mid - 1;
}
```

30.
```cpp
for(int i = 0; i < n1; i++) {
    for(int j = 0; j < n2; j++) {
        if(arr1[i] == arr2[j]) cout << arr1[i] << " ";
    }
}
```

31.
```cpp
int temp[n1 + n2], k = 0;
for(int i = 0; i < n1; i++) temp[k++] = arr1[i];
for(int i = 0; i < n2; i++) {
    bool exists = false;
    for(int j = 0; j < k; j++) if(arr2[i] == temp[j]) exists = true;
    if(!exists) temp[k++] = arr2[i];
}
```

32.
```cpp
for(int i = 0; i < n; i++) {
    for(int j = i + 1; j < n; j++) {
        if(arr[i] == arr[j]) return arr[i];
    }
}
```

33.
```cpp
bool hasDup = false;
for(int i = 0; i < n; i++) {
    for(int j = i + 1; j < n; j++) {
        if(arr[i] == arr[j]) hasDup = true;
    }
}
```

34.
```cpp
int prefix[n];
prefix[0] = arr[0];
for(int i = 1; i < n; i++) prefix[i] = prefix[i - 1] + arr[i];
```

35.
```cpp
int pos[n], neg[n], p = 0, q = 0;
for(int i = 0; i < n; i++) {
    if(arr[i] >= 0) pos[p++] = arr[i];
    else neg[q++] = arr[i];
}
int i = 0;
for(int j = 0; j < min(p, q); j++) {
    arr[i++] = pos[j];
    arr[i++] = neg[j];
}
while(j < p) arr[i++] = pos[j++];
while(j < q) arr[i++] = neg[j++];
```

---

✨ *These solutions help solidify understanding of array concepts, from foundational usage to algorithmic logic.*
