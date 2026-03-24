# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length=5, breadth=3):
        self.__length = length
        self.__breadth = breadth
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

rect = Rectangle()

```
## Output


<img width="359" height="184" alt="image" src="https://github.com/user-attachments/assets/6150027c-9690-41c1-9593-5eb6d8439152" />

## Result

Thus, the Python program successfully demonstrates private attributes in a class and displays their values using the constructor.
