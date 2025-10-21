# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
class Tiger():
    def nature(self):
        print("I am a Tiger and I am dangerous.")
    def color(self):
        print("Tigers are orange with black strips")

class Elephant():
    def nature(self):
        print("I am an Elephant and I am calm and harmless")
    def color(self):
        print("Elephants are grayish black")
obj1 = Tiger()
obj2 = Elephant()

for animal in (obj1, obj2):
    animal.nature()
    animal.color()
## Output

<img width="1018" height="323" alt="image" src="https://github.com/user-attachments/assets/8e357bca-73e5-4045-b5a3-38dfa6d34441" />

## Result
Thus the python program is executed successfully.
