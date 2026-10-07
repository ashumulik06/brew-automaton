# ☕ Coffee Vending Machine Using Deterministic Finite Automaton (DFA)

An interactive web application that demonstrates the working of a **Coffee Vending Machine** using the concepts of **Deterministic Finite Automata (DFA)** from the Theory of Computation. The project provides a visual representation of state transitions, transition functions, accepted/rejected strings, and real-time DFA execution.

---

## 🚀 Live Demo

https://ashumulik06.github.io/brew-automaton/

---

## 📌 Project Overview

This project models a coffee vending machine as a **Deterministic Finite Automaton (DFA)**. Every user action (coin insertion, buying coffee, or resetting the machine) is considered an input symbol that causes the machine to transition from one state to another according to the DFA transition function.

The application is designed for educational purposes to help students understand how Formal Language and Automata Theory concepts can be applied to real-world systems.

---

## 🎯 Objectives

- Demonstrate the practical application of DFA.
- Simulate a real-world coffee vending machine.
- Visualize deterministic state transitions.
- Explain Formal Language concepts interactively.
- Bridge theoretical concepts with practical implementation.

---

# ✨ Features

## ☕ Coffee Vending Features

- Insert ₹5, ₹10 and ₹20 coins
- Buy coffee after sufficient balance
- Reset vending machine
- Real-time balance calculation
- Coffee dispensing animation
- Transaction history

---

## 🔄 DFA Features

- Deterministic State Transitions
- Interactive State Space Overview
- Transition Table
- Current State Tracking
- Current Input Display
- Next State Display
- Current DFA Transition
- Transition Function Visualization
- Accept State Detection
- Reject/Error State Handling
- Live DFA Execution

---

## 📚 Educational Features

- Formal DFA Definition
- Set of States (Q)
- Input Alphabet (Σ)
- Transition Function (δ)
- Initial State (q₀)
- Final State (F)
- Accepted & Rejected Strings
- State Transition Explanation

---

## 🆕 Newly Added Features

- 📊 Conventional vs DFA-Based Coffee Vending Machine Comparison
- 📈 Interactive Comparison Graph
- ⚡ DFA Animation Speed Control
  - Slow
  - Medium
  - Fast
- Improved DFA Visualization
- Better Educational Representation
- Enhanced User Experience

---

# 🧠 DFA Representation

## States (Q)

```
Q = {q0, q5, q10, q15, ..., q100, qAccept, qError}
```

---

## Input Alphabet (Σ)

```
Σ = {₹5, ₹10, ₹20, BUY, RESET}
```

---

## Initial State

```
q0
```

---

## Final State

```
F = {qAccept}
```

---

## Sample Transition Function

```
δ(q0, ₹5) = q5

δ(q5, ₹10) = q15

δ(q20, BUY) = qAccept

δ(qAny, RESET) = q0
```

---

# 🔄 DFA Workflow

```
                Start (q0)
                    │
                    ▼
            Insert Coin
                    │
                    ▼
          Update Current State
                    │
                    ▼
          Enough Balance?
             │          │
            No         Yes
             │          │
             ▼          ▼
        Wait Input    BUY
                         │
                         ▼
                   Accept State
                         │
                         ▼
                Dispense Coffee
                         │
                         ▼
                       Finish
```

---

# 📊 Conventional vs DFA-Based System

| Feature | Conventional System | DFA-Based System |
|----------|---------------------|------------------|
| State Tracking | Basic | DFA States |
| Transition Logic | Program Logic | Mathematical DFA |
| State Diagram | ❌ | ✅ |
| Transition Function | ❌ | ✅ |
| Accept/Reject State | ❌ | ✅ |
| Interactive Visualization | ❌ | ✅ |
| Educational Purpose | Low | High |
| Animation | Limited | Interactive |
| Theory of Computation | ❌ | ✅ |

---

# 📈 Performance Comparison

The project includes an interactive comparison graph between:

- Conventional Coffee Vending Machine
- DFA-Based Coffee Vending Machine

The graph compares:

- State Tracking
- Accuracy
- Educational Value
- Visualization
- Deterministic Behaviour
- User Understanding

---

# ⚡ Animation Speed

Users can control the execution speed of DFA animations.

Available Modes:

- 🐢 Slow
- 🚶 Medium
- ⚡ Fast

This helps users understand state transitions at different speeds.

---

# 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- SVG
- GitHub Pages

---

# 📂 Project Structure

```
CoffeeVending-DFA/
│
├── index.html
├── style.css
├── script.js
├── assets/
├── images/
├── README.md
└── LICENSE
```

---

# 🎓 Learning Outcomes

After using this project, users can understand:

- Deterministic Finite Automata (DFA)
- Formal Languages
- Transition Functions
- State Machines
- Accepted and Rejected Strings
- Real-world DFA Applications
- Interactive Algorithm Visualization

---

# 📸 Project Highlights

- ☕ Coffee Vending Machine Simulation
- 🔄 Interactive DFA Execution
- 📊 Transition Table
- 📌 Current State Tracking
- ⚡ DFA Speed Controller
- 📈 Performance Comparison Graph
- 📚 Educational Visualization
- 🎯 Accept/Reject State Detection
- 🧠 Formal DFA Representation

---

# 🎯 Future Enhancements

- Multiple Coffee Options
- Coin Return Feature
- Change Calculation
- NFA to DFA Conversion Module
- PDA & Turing Machine Simulations
- Sound Effects
- Mobile App Version

---

# 👨‍💻 Author

**Ashu Mulik**

B.Tech Computer Engineering

Rajarambapu Institute of Technology

---

# ⭐ If you found this project useful, don't forget to star the repository!
