# STUDY-OF-SETS-AND-DICTIONARY-IN-PYTHON

Perfect 👍
Below is a **clean, professional README.md** you can directly copy–paste for your **Experiment 5**.
(No extra drama, lab-record + GitHub ready.)

---

#  Experiment 5

## Study of Sets and Dictionaries in Python

### Student Information

* **Name:** Amey Waghmare
* **PRN:** 25070123009
* **Division:** A1
* **Subject:** Python Programming

---

##  Aim

To study **Sets, Frozensets, and Dictionaries in Python** and perform various operations such as creation, modification, searching, and set-theoretic operations.

---

##  Theory

###  Set in Python

A set is a collection of:

* Unique elements (no duplicates)
* Unordered items
* Mutable (elements can be added or removed)

Sets are based on **mathematical set theory**.

---

###  Frozenset

A frozenset is an **immutable set**, meaning:

* Elements cannot be added or removed after creation
* Supports all set operations like union, intersection, etc.

---

###  Dictionary in Python

A dictionary:

* Stores data in **key–value pairs**
* Does not allow duplicate keys
* Is mutable
* Uses keys to access values efficiently

---

##  Programs & Observations

### 1️ Creation of Set

```python
thisset = {"Ferrari", "Lamborghini", "Bugatti"}
print(thisset)
```

---

### 2️ Duplicate Elements Not Allowed

```python
thisset = {"Ferrari", "Lamborghini", "Bugatti", "Ferrari"}
print(thisset)
```

---

### 3️ Boolean Values in Set

```python
thisset = {"Ferrari", True, False, 0, 1}
print(thisset)
```

---

### 4️ Mixed Data Types in Set

```python
set1 = {"ferrari", 7, True, 18, "Lamborghini", False, 3+4j}
print(set1)
```

---

### 5️ Searching an Element

```python
thisset = {"Ferrari", "Lamborghini", "Bugatti"}
print("Lamborghini" in thisset)
```

---

### 6️ Add and Remove Elements

```python
thisset.add("BMW")
thisset.remove("Bugatti")
```

---

### 7️ Set Operations

```python
A = {"Ferrari", "Lamborghini", "Bugatti"}
B = {"BMW", "Ferrari", "Lamborghini"}

print("Union:", A | B)
print("Intersection:", A & B)
print("Difference:", A - B)
print("Symmetric Difference:", A ^ B)
```

---

### 8️ Frozenset Operations

```python
A = frozenset({"Ferrari", "Lamborghini", "Bugatti"})
B = frozenset({"BMW", "Ferrari", "Lamborghini"})
```

---

### 9️ Dictionary Creation & Modification

```python
car = {
    "brand": "BMW",
    "model": "M series",
    "year": 2000
}
car["color"] = "Black"
```

---

###  Dictionary Problem Statements

* Store student marks
* Find maximum marks and topper
* User login validation
* Product price update

Example:

```python
student_marks = {
    "A": 70,
    "B": 65,
    "C": 75
}

topper = max(student_marks, key=student_marks.get)
print("Topper:", topper)
```

---

##  Result

All set, frozenset, and dictionary operations were successfully executed and verified using Python programs.

---

##  Conclusion

This experiment helped in understanding:

* Properties of sets and frozensets
* Set-theoretic operations
* Practical use of dictionaries in real-world problems

---

##  Tools Used

* Python 3
* Jupyter Notebook / Google Colab / VS Code



