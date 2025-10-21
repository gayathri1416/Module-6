# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
class A:
    def __init__(self,value):
        self.value=value
    def __lt__(self,other):
        return self.value<other.value
ob1=A(20)
ob2=A(10)
if ob1<ob2:
    print("True")
else:
    print("False")
## Output
<img width="568" height="207" alt="image" src="https://github.com/user-attachments/assets/435cfcbb-a0ee-4e2c-9e45-8093531d5ba5" />

## Result
Thus the python program is executed successfully.
