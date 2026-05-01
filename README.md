# Fuzzy Autonomous Driving Simulation

## 📌 Overview
This project implements a **Fuzzy Inference System (FIS)** to simulate basic autonomous driving behavior.  
The system uses fuzzy logic to make real-time decisions such as **acceleration, braking, and steering** based on environmental inputs.

---

## 🎯 Objectives
- Apply fuzzy logic for intelligent decision-making  
- Simulate autonomous vehicle control  
- Handle uncertainty in real-world inputs  
- Build an interactive simulation system  

---

## 🧠 Concepts Used
- Fuzzy Sets  
- Membership Functions  
- Fuzzy Rules  
- Mamdani Inference System  
- Defuzzification  

---

## ⚙️ Inputs and Outputs

### Inputs
- Distance from obstacle  
- Vehicle speed  
- Lane position  

### Outputs
- Acceleration (Brake / Maintain / Accelerate)  
- Steering (Left / Straight / Right)  

---

## 🏗️ Project Structure
```
fuzzy-car-simulation-project/
│
├── main.py
├── fuzzy.py
├── sensors.py
├── monitor.py
├── elements/
├── imgs/
├── requirements.txt
└── .gitignore

```
---

## 🔄 Working Flow
1. Sensor data is collected  
2. Inputs are converted into fuzzy values  
3. Fuzzy rules are applied  
4. Output is defuzzified  
5. Vehicle control is executed  

---

## 🔥 Example Rules
- IF distance is Near → Brake  
- IF distance is Far AND speed is Slow → Accelerate  
- IF lane deviation is Left → Turn Right  

---

## 🛠️ Technologies Used
- Python  
- Pygame  
- NumPy  
- Fuzzy Logic  

---

## ▶️ How to Run

### Clone repository
```bash
git clone https://github.com/vaibhavraok/fuzzy-car-simulation-project.git
cd fuzzy-car-simulation-project
pip install -r requirements.txt
python main.py

