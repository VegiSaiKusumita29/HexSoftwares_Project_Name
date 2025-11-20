# Fibonacci Series Generator (Python)  
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  

## 📌 Project Overview  
This repository contains a simple Python program that generates the Fibonacci series based on user input. It’s designed to help build and demonstrate foundational programming concepts such as loops, variable assignment, and sequence generation.

---

## 🚀 Features  
- Prompts the user for how many terms of the Fibonacci sequence to generate  
- Prints the Fibonacci series in a single line separated by spaces  
- Written in Python 3 and easy for beginners to understand  

---

## 🧩 How It Works  
The program initializes two variables `a` and `b` with the first two values of the sequence (0 and 1). In each iteration of a loop:
1. It prints the current value of `a`  
2. Updates the variables so that `a` becomes the previous `b`, and `b` becomes the sum of the old `a` and `b`  
3. Repeats until the desired number of terms is reached  

---

## 🧮 Code Snippet  
```python
n = int(input("Enter how many terms you want: "))

a, b = 0, 1
print("Fibonacci Series:")

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

---

## 📂 Project Structure  
```
HexSoftwares_Project_Name/
│── Fibinocii.py
│── README.md
```

---

## 📦 How to Run the Program  
1. Ensure you have **Python 3** installed on your machine  
2. Clone or download this repository  
   ```bash
   git clone https://github.com/VegiSaiKusumita29/HexSoftwares_Project_Name.git
   ```  
3. Navigate into the project folder and run the script:  
   ```bash
   python Fibinocii.py
   ```  
4. Follow the prompt to enter the number of terms you’d like to generate  

---

## 🛠️ Tech Stack  
- **Language:** Python (3.x)

---

## ✨ Future Enhancements  
- Add a **recursive function** version of the Fibonacci series  
- Add **graphical user interface (GUI)** using Tkinter or PyQt  
- Implement **error handling** for invalid inputs (like non-integers, negative numbers)  
- Add **unit tests** to validate correct sequence generation  

---

## 👤 Author & Contact  
**Sai Kusumita Vegi**  
🔗 GitHub: [VegiSaiKusumita29](https://github.com/VegiSaiKusumita29)  
Feel free to connect with me on LinkedIn or drop a message if you'd like to collaborate!

---

## 📄 License  
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

