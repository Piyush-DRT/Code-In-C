# ✅ C++ Strings – Solutions to Practice Problems

This file contains answers and logic to all 35 string practice questions, across 4 levels.

---

## 🟢 Category 1: Output-Based Questions

1. `5`

2. `zbc`

3. `s`

4. `123456`

5. `C-+-+-`

---

## 🟡 Category 2: Basic String Operations

6.
```cpp
int count = 0;
for(char c : s) {
    if(strchr("aeiouAEIOU", c)) count++;
}
```

7.
```cpp
int alpha = 0, digit = 0, special = 0;
for(char c : s) {
    if(isalpha(c)) alpha++;
    else if(isdigit(c)) digit++;
    else special++;
}
```

8.
```cpp
reverse(s.begin(), s.end());
```

9.
```cpp
for(char &c : s) c = toupper(c);
```

10.
```cpp
for(char &c : s) c = tolower(c);
```

11.
```cpp
int count = 0;
for(char c : s) if(c == x) count++;
```

12.
```cpp
bool isPalin = true;
for(int i = 0; i < s.length() / 2; i++)
    if(s[i] != s[s.length()-i-1]) isPalin = false;
```

13.
```cpp
string res;
for(char c : s) if(c != ' ') res += c;
```

14.
```cpp
for(char c : s) {
    if(count(s.begin(), s.end(), c) == 1) { cout << c; break; }
}
```

15.
```cpp
for(char &c : s) if(c == ' ') c = '-';
```

---

## 🟠 Category 3: Logic Building

16.
```cpp
for(char &c : s) {
    if(isupper(c)) c = tolower(c);
    else if(islower(c)) c = toupper(c);
}
```

17.
```cpp
int count = 1;
for(char c : s) if(c == ' ') count++;
```

18.
```cpp
sort(s1.begin(), s1.end());
sort(s2.begin(), s2.end());
if(s1 == s2) cout << "Anagram";
```

19.
```cpp
string res;
for(char c : s) {
    if(res.find(c) == string::npos) res += c;
}
```

20.
```cpp
stringstream ss(s);
string word, longest;
while(ss >> word) if(word.length() > longest.length()) longest = word;
```

21.
```cpp
bool capitalize = true;
for(char &c : s) {
    if(capitalize && isalpha(c)) {
        c = toupper(c);
        capitalize = false;
    } else if(c == ' ') capitalize = true;
}
```

22.
```cpp
string res;
int i = 0;
while(i < s.length()) {
    char c = s[i];
    int count = 1;
    while(i + 1 < s.length() && s[i] == s[i+1]) {
        count++; i++;
    }
    res += c + to_string(count);
    i++;
}
```

23.
```cpp
for(int i = 0; i < s.length(); i++) {
    for(int j = 1; j <= s.length() - i; j++) {
        cout << s.substr(i, j) << endl;
    }
}
```

24.
```cpp
for(char c = 'a'; c <= 'z'; c++) {
    if(s1.find(c) != string::npos && s2.find(c) != string::npos)
        cout << c;
}
```

25.
```cpp
bool isDigit = true;
for(char c : s) if(!isdigit(c)) isDigit = false;
```

---

## 🔴 Category 4: DSA-Level String Problems

26. Use dynamic programming (O(n^2)) to check all substrings for palindrome.

27.
```cpp
unordered_set<char> seen;
for(char c : s) {
    if(seen.count(c)) return c;
    seen.insert(c);
}
```

28.
```cpp
if(s1.length() == s2.length() && (s1 + s1).find(s2) != string::npos) cout << "Yes";
```

29. Use backtracking/recursion to generate all permutations.

30.
```cpp
unordered_map<string, int> freq;
stringstream ss(s);
string word;
while(ss >> word) freq[word]++;
```

31.
```cpp
if(s.find(pattern) != string::npos) cout << "Found";
```

32.
```cpp
sort(arr.begin(), arr.end());
string prefix = arr[0];
for(int i = 1; i < arr.size(); i++) {
    while(arr[i].find(prefix) != 0) prefix.pop_back();
}
```

33.
```cpp
int freq1[26] = {0}, freq2[26] = {0};
for(char c : s1) freq1[c-'a']++;
for(char c : s2) freq2[c-'a']++;
int count = 0;
for(int i = 0; i < 26; i++) count += abs(freq1[i] - freq2[i]);
```

34. Use map of sorted string as key, group original strings as values.

35. Sliding window + hash count (like in "minimum window substring").

---

✨ These solutions help students build character-by-character manipulation, STL practice, and algorithmic intuition in strings.
