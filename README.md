# HashTable in Java

This project demonstrates a simple **Hash Table** implementation in Java using **separate chaining** with `LinkedList`. It maps `int` keys (e.g., roll numbers) to `String` values (e.g., student names).

## 💡 Features

- Stores key-value pairs (roll number → student name)
- Handles collisions using **separate chaining**
- Automatically replaces value if key already exists
- Simple CLI-based input for searching student name by roll number

## 📁 Project Structure

src/
└── com/
└── hashtable/
├── HashTableMain.java
└── (HashTable class defined here)


## 📌 Sample Output
Added: Pair [key=1, value=Nilesh]
Added: Pair [key=4, value=Nitin]
...
Enter roll to find:
1
Name found: Rohan

