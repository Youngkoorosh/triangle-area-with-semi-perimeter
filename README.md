# 📏 Triangle Area with Semi-Perimeter

This Python script calculates the area of a triangle using **only its three side lengths** (`a`, `b`, `c`). It implements **Heron's Formula**, emphasizing both the geometric concept of semi-perimeter and precision in output.

## 🚀 What's Inside

- Input :
- Three integers as side lengths
- 
- Logic :
  1. Calculates the semi-perimeter `p = (a + b + c) / 2`
  2. Computes the area using Heron's formula
  3. Prints the result with **9-digit precision**

### 🧠 Formula Recap

#### Semi-perimeter:
```bash
p = (a + b + c) / 2
```

#### Area:
```bash
s = sqrt(p * (p - a) * (p - b) * (p - c))
```

### 📄 Sample Code

```python
a, b, c = map(int, input().split())
p = (a + b + c) / 2
s = (p * (p - a) * (p - b) * (p - c)) ** 0.5
print(f"{s: .9f}")
```
# 🧪 Example Run
## Input:
```bash
3 4 5
```
## Output:
```bash
 6.000000000
```
# 🎯 Why This Matters
* Builds intuition for semi-perimeter and triangle geometry
* Showcases Python’s precision formatting with f"{value: .9f}"
* Great practice for math-related problem-solving and input parsing\

# 👨🏻‍🚀 Author
Made with care by Koorosh Feel free to fork, star, or improve!
