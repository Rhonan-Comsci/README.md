[README-2.md](https://github.com/user-attachments/files/23839219/README-2.md)

# Ticket Redemption System

## Group 5: Narra
**Members**
- Batalon, Rhonan
- Carolino, Daren
- Pascua, Andrei

---

## Project Description
The **Ticket Redemption System** is a Python program that allows users to redeem arcade prizes using their collected tickets. The user inputs their ticket count, views available prizes, and chooses one to redeem. The system validates inputs, checks ticket sufficiency, deducts costs, and shows remaining tickets.

---

## Objectives
- Create a functional program using Python  
- Practice input validation and selection structures  
- Use at least one user-defined function  
- Display results clearly and accurately  
- Apply proper code documentation and a README file  

---

## Requirements
**Programming Language:** Python  
**IDE:** Visual Studio Code  
**Built-in Methods:** `print()`, `input()`, `int()`, `isdigit()`

---

## Features
- Display available prizes and ticket costs  
- Accept and validate ticket input  
- Allow user to choose a prize (1–3)  
- Check if the user has enough tickets  
- Redeem prize and display remaining tickets  

---

## Function(s) Used
### `show_prizes()`
Displays the prize list with corresponding ticket costs.

---

## Input & Validation
- **Tickets:** Must be numeric using `isdigit()`  
- **Prize Choice:** Must be an integer from 1 to 3  


---


## Sample Output:
    Welcome to the Ticket Redemption System!
    Enter the number of tickets you have: 20
    Available prizes:

    Stuffed Toy - 15 tickets

    Keychain - 5 tickets

    Candy - 2 tickets
    Choose a prize (1-3): 1
    You redeemed a Stuffed Toy! Tickets left: 5
---

## Logic Flow
1. Start  
2. Display welcome message  
3. Ask user for number of tickets  
4. Validate ticket input  
5. Show prize list  
6. Ask for prize choice  
7. If choice is valid:  
   - **1:** Check if ≥ 15 tickets  
   - **2:** Check if ≥ 5 tickets  
   - **3:** Check if ≥ 2 tickets  
8. If enough tickets → redeem and update balance  
9. If not enough → show error  
10. If invalid choice → show error  
11. End  

---

## References
- W3Schools: Python `isdigit()`  
https://www.w3schools.com/python/ref_string_isdigit.asp

- W3Schools: Python `int()`
https://www.w3schools.com/python/ref_func_int.asp




