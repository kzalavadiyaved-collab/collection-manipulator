# 🎓 Student Data Organizer

A dynamic Python project that demonstrates the use of **String Formatting**, **Collection Data Types**, **Mutability & Immutability**, **Type Casting**, and the **del keyword** by managing student records.

---

# 📌 Project Objective

The Student Data Organizer is a console-based Python application that stores and manages student information using different collection data types.

The project demonstrates:

- ✅ String Formatting
- ✅ List
- ✅ Tuple
- ✅ Set
- ✅ Dictionary
- ✅ Type Casting
- ✅ Mutability & Immutability
- ✅ del Keyword

---

# 🚀 Features

- Add new student records
- Display all students
- Search student by ID
- Update student details
- Delete student records
- Display all unique subjects
- Demonstrate mutable and immutable collections
- Demonstrate different string formatting methods

---

# 📂 Data Structures Used

## 1️⃣ List (Mutable)

Stores multiple student records.

Example:

```python
students = []
```

---

## 2️⃣ Tuple (Immutable)

Stores fixed information like Student ID and Date of Birth.

Example:

```python
student_info = (101, "12-05-2005")
```

---

## 3️⃣ Set

Stores unique subjects.

Example:

```python
subjects = {"Python", "Java", "C++"}
```

---

## 4️⃣ Dictionary

Stores student information.

Example:

```python
students = {
    101: {
        "name": "Rahul",
        "age": 20,
        "grade": "A",
        "subjects": ["Python", "Java"]
    }
}
```

---

# 🖥 Menu

```
==============================
 STUDENT DATA ORGANIZER
==============================

1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Show Unique Subjects
7. Exit
```

---

# 📥 Input

Example:

```
Enter Student ID : 101
Enter Name : Rahul
Enter Age : 20
Enter Grade : A
Enter DOB : 12-05-2005
Enter Subjects : Python,Java,C++
```

---

# 📤 Output

```
-----------------------------
Student ID : 101
Name       : Rahul
Age        : 20
Grade      : A
DOB         : 12-05-2005
Subjects   : Python, Java, C++
-----------------------------
```

---

# 🎯 String Formatting Used

## f-string

```python
print(f"Name : {name}")
```

## format()

```python
print("Age : {}".format(age))
```

## % Formatting

```python
print("Grade : %s" % grade)
```

---

# 🔄 Type Casting

```python
age = int(input("Enter Age : "))
percentage = float(input("Enter Percentage : "))
```

---

# 📝 Mutability Example

```python
students.append(data)
students[0]["grade"] = "A+"
```

---

# 🔒 Immutability Example

```python
student_info = (101, "12-05-2005")

# student_info[0] = 102
# ❌ Error
```

---

# 🗑 del Keyword Example

```python
del students[101]
```

---

# 💻 Technologies

- Python 3.x
- VS Code / PyCharm / IDLE

---

# 📁 Project Structure

```
Student-Data-Organizer/
│
├── main.py
├── README.md
└── screenshots/
```

---

# ▶️ How to Run

Clone the project

```bash
git clone <repository-url>
```

Go to project folder

```bash
cd Student-Data-Organizer
```

Run

```bash
python main.py
```

---

# 📚 Python Concepts Covered

| Concept | Status |
|----------|--------|
| Input/Output | ✅ |
| String Formatting | ✅ |
| List | ✅ |
| Tuple | ✅ |
| Set | ✅ |
| Dictionary | ✅ |
| Type Casting | ✅ |
| del Keyword | ✅ |
| Functions | ✅ |
| Loops | ✅ |
| Conditional Statements | ✅ |

---

# 👨‍💻 Author

**Student Data Organizer**

Python Collection Manipulator Project

---

# ⭐ Sample Workflow

```
Start Program
      │
      ▼
Display Menu
      │
      ▼
Select Option
      │
      ├── Add Student
      ├── View Students
      ├── Search Student
      ├── Update Student
      ├── Delete Student
      ├── Show Subjects
      └── Exit
```

---

# 📌 Expected Learning Outcomes

After completing this project, you will understand:

- Working with Lists
- Using Tuples for immutable data
- Managing unique data using Sets
- Organizing records using Dictionaries
- String Formatting methods
- Type Casting
- del keyword
- CRUD operations in Python
- Basic Data Management System

---

⭐ **This project is designed for beginners to practice Python Collection Data Types and Intermediate Python Concepts.**
