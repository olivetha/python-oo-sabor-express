# 🍽️ Python OOP - Sabor Express

Welcome to **Sabor Express**, a simple restaurant review app built during my journey learning Object-Oriented Programming (OOP) with Python!

This project was developed as part of a hands-on course focused on OOP fundamentals — from creating classes to composing objects and writing clean, pythonic code.

---

## 🚀 Features

- Create restaurants with name, category, and active status  
- Activate/deactivate restaurants  
- Add reviews to restaurants (with rating and comment)  
- List all reviews for a specific restaurant  
- Use of `__str__` to print friendly object representations

---

## 🧠 What I Learned

- Class creation and instance attributes  
- Special methods (`__init__`, `__str__`)  
- Class methods  
- Pythonic attribute writing (e.g., no need for getters/setters)  
- Object composition (Restaurant has a list of Review objects)

---

## 📂 Project Structure

├── main.py # Entry point ├── restaurante.py # Restaurant class definition └── avaliacao.py # Review class definition


---

## 🛠️ How to Run

Make sure you have Python installed.  
Then clone the repo and run:

```bash
python main.py

## 📸 Example Output
--- Restaurant Info ---
Name: Sabor Express
Category: Fast Food
Active: False

Activating restaurant...
Restaurant is now active ✅

Adding reviews...
- Rating: 5, Comment: Amazing food!
- Rating: 4, Comment: Great service!

Listing reviews...
1. ⭐ 5 - Amazing food!
2. ⭐ 4 - Great service!

## 📎 Course Info
This project was developed during the Santander TECH+ Python OOP course, a great way to learn the fundamentals of object-oriented programming in a fun, hands-on way.
