# 🃏 Blackjack — Python Project  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)
![DaysOfCode](https://img.shields.io/badge/90DaysOfCode-Python%20Challenge-9cf)

A modular, text-based implementation of the **classic Blackjack card game** built using Python.  
This project is part of my **#90DaysOfCode challenge**, focusing on improving logic building, modular design, and interactive user experience in Python.

---

## 🚀 Features

✅ Play a full Blackjack game against a computer dealer  
✅ Smart Ace handling (automatically switches from 11 → 1 when needed)  
✅ Detects Blackjack, busts, draws, and wins automatically  
✅ Randomized card dealing for every round  
✅ Simple, clean, and ASCII-enhanced command-line interface  
✅ Modular function-based design for reusability  

---

## 🧠 What I Learned

- Building modular programs using reusable functions  
- Implementing Blackjack rules and game logic in Python  
- Using loops and conditionals for turn-based gameplay  
- Handling user input and controlling game flow  
- Designing clean, readable CLI interactions  

---

## 💻 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/faizhsnnn/Blackjack.git
cd Blackjack
```
# 2️⃣ Run the Game
```bash
python blackjack.py
```
---

# 🧩 Example Run
```bash
Do you want to play a game of Blackjack? Type 'y' or 'n': y

                                                                                   
88          88                       88        88                       88         
88          88                       88        ""                       88         
88          88                       88                                 88         
88,dPPYba,  88 ,adPPYYba,  ,adPPYba, 88   ,d8  88 ,adPPYYba,  ,adPPYba, 88   ,d8   
88P'    "8a 88 ""     `Y8 a8"     "" 88 ,a8"   88 ""     `Y8 a8"     "" 88 ,a8"    
88       d8 88 ,adPPPPP88 8b         8888[     88 ,adPPPPP88 8b         8888[      
88b,   ,a8" 88 88,    ,88 "8a,   ,aa 88`"Yba,  88 88,    ,88 "8a,   ,aa 88`"Yba,   
8Y"Ybbd8"'  88 `"8bbdP"Y8  `"Ybbd8"' 88   `Y8a 88 `"8bbdP"Y8  `"Ybbd8"' 88   `Y8a  
                                              ,88                                  
                                            888P"                                  
Your cards : [10, 7], Current score: 17
Computer's first card 6
Type 'y' to get another card, type 'n' to pass: n

Your final hand is: [10, 7], final score: 17
Computer's final hand is: [6, 10, 8], final score: 24
Opponent went over. You win 🎉
```
---

# 🧾 File Structure
```
Blackjack/
│
├── blackjack.py       # Main Python program (game logic)
├── ascii.py           # ASCII art logo for the interface
└── README.md          # Project documentation
```
---

# ✨ Code Highlights

if 11 in cards and sum(cards) > 21:
    cards.remove(11)
    cards.append(1)


♣️ Handles the Ace smartly — converts 11 to 1 if total exceeds 21.

if user_score == 0:
    return "Win with a Blackjack"
elif computer_score == 0:
    return "Lose, opponent has Blackjack"


🏆 Detects instant Blackjack wins and losses.

---

# 🔮 Future Improvements

- ✅ Add betting system and virtual chips
- ✅ Create a GUI version using Tkinter or Pygame
- ✅ Add multiplayer support
- ✅ Implement score history tracking
- ✅ Add difficulty levels for the computer dealer

---

# 👨‍💻 Author

- Faiz Hasan 🎓
- BCA Final Year @ Graphic Era University
- 🚀 #90DaysOfCode | 🐍 Python Learner | 🎮 Logic & Game Dev Enthusiast

---


*🖋️ "Logic is the heart of every great program — simplicity makes it shine."*
