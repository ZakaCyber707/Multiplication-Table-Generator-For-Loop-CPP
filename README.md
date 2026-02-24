# Multiplication Table Generator (For Loop)



## 📖 Overview
This repository contains a C++ program designed to automate the generation of multiplication tables. It highlights the efficiency of the `for` loop in handling repetitive arithmetic operations.

## ⚙️ Logic Architecture
The program executes through a simple yet effective iteration process:
1. **User Input:** Captures the base number (`num`) for the table.
2. **The Loop:** Runs exactly 10 times, incrementing a counter (`i`) from 1 to 10.
3. **Calculation & Formatting:** Multiplies `num * i` and prints it in a formatted string (e.g., `5 x 1 = 5`).



## 🛠️ Features
* **Dynamic Generation:** Works for any integer entered by the user.
* **Clean Formatting:** Uses `endl` to ensure each entry in the table appears on a new line.
* **Lightweight:** Minimal memory footprint using standard I/O.

## 💻 How to Run
1. **Compile:** `g++ MultiplicationTable.cpp -o TableGen`
2. **Run:** `./TableGen`
