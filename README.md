# ICS 4111: Practical Exercise 3 — Embedded Design
## Objective: Practical Demonstration of Ohm’s Law

This repository contains the documentation, schematic implementations, and findings for Practical Exercise 3, focusing on the practical application of Ohm's Law using an Arduino microcontroller, breadboard, resistors, LEDs, and a multimeter.

---

## 👥 Team Evidence
> **Submission Requirement:** 50% of the final score relies on teamwork validation. Below is the evidence of our group collaboration.

![Group Photo / Meeting Screenshot](images/groupphoto.jpeg)

### Group Members & Attendance
| Student Name | Student ID | Role / Contribution | Attendance |
| :--- | :--- | :--- | :---: |
| Member 1 | 123456 | Experiment 1 & 2 Setup | Physical / Online |
| Member 2 | 123456 | Experiment 3 & 4 Setup | Physical / Online |
| Member 3 | 123456 | Multimeter Readings & Data | Physical / Online |
| Member 4 | 123456 | Documentation & GitHub | Physical / Online |

---

## 🔬 Experiment 1: Resistor Value Verification

### 1. Color Code Identification
* **Selected Resistor Bands:** [e.g., Brown, Black, Red, Gold]
* **Determined Resistance Value (Nominal):** `_______ Ω`

![Resistor Color Code Setup](path/to/resistor_color_code.png)

### 2. Multimeter Measurement
* **Measured Resistance Value:** `_______ Ω`

![Multimeter Resistance Measurement](path/to/multimeter_resistance.png)

### 📊 Summary Table
| Method | Resistance Value (Ω) |
| :--- | :--- |
| **Nominal (Color Code)** | `____ Ω` |
| **Measured (Multimeter)** | `____ Ω` |

### 💬 Experiment Reflection
**Question:** Where does the difference in the resistance values arise from?

> **Answer:** > [Insert your reflection here. *Hint: Consider component manufacturing tolerances (the 4th/5th color band like Gold ±5% or Silver ±10%), multimeter calibration, probe resistance, and ambient temperature.*]

---

## 💡 Experiment 2: LED Circuit & Pulse Width Modulation (PWM)

### 1. Basic Circuit Schematic & Implementation
The Blink program was deployed using the Arduino IDE to control the LED circuit.

![Physical Implementation of Basic LED Circuit](path/to/basic_led_circuit.png)

* **Measured Circuit Voltage:** `_______ V` (via Multimeter)

---

### 2. PWM Light Intensity Control (Potentiometer Integration)
A potentiometer was added to simulate Pulse Width Modulation (PWM) and control the LED brightness levels dynamically.

#### 📸 Circuit Brightness Levels
| 25% Brightness | 50% Brightness | 100% Brightness |
| :---: | :---: | :---: |
| ![25% Brightness](path/to/led_25.png) | ![50% Brightness](path/to/led_50.png) | ![100% Brightness](path/to/led_100.png) |
| *LED at 25% duty cycle* | *LED at 50% duty cycle* | *LED at 100% duty cycle* |

---

## 🔗 Experiment 3: Resistors in Series

### 1. Physical Implementation
The circuit was reconfigured to connect two resistors in a series configuration alongside the LED.

![Series Circuit Implementation](path/to/series_circuit.png)

### 📊 Voltage Readings
* **Voltage Across Resistor 1 ($V_{R1}$):** `_______ V`
* **Voltage Across Resistor 2 ($V_{R2}$):** `_______ V`
* **Total Voltage Across Resistors ($V_{Total}$):** `_______ V`

### 💬 Experiment Reflection
**Question:** Use Ohm’s Law ($I = V / R$) to estimate the current passed at each resistor.

> **Calculations:**
> * **Current through $R_1$ ($I_1$):** $I_1 = V_{R1} / R_1$ = `_______ A` (or `___ mA`)
> * **Current through $R_2$ ($I_2$):** $I_2 = V_{R2} / R_2$ = `_______ A` (or `___ mA`)
>
> **Conclusion:** > [Insert your observation here. *Hint: In a series circuit, what do you notice about the current flowing through each components?*]

---

## ⚡ Experiment 4: Resistors in Parallel

### 1. Physical Implementation
The circuit was reconfigured to connect both resistors in a parallel configuration.

![Parallel Circuit Implementation](path/to/parallel_circuit.png)

### 📊 Voltage Readings
* **Voltage Across Resistor 1 ($V_{R1}$):** `_______ V`
* **Voltage Across Resistor 2 ($V_{R2}$):** `_______ V`

### 💬 Experiment Reflection
**Question:** Use Ohm’s Law ($I = V / R$) to estimate the current passed at each resistor.

> **Calculations:**
> * **Current through $R_1$ ($I_1$):** $I_1 = V_{R1} / R_1$ = `_______ A` (or `___ mA`)
> * **Current through $R_2$ ($I_2$):** $I_2 = V_{R2} / R_2$ = `_______ A` (or `___ mA`)
> * **Total Circuit Current ($I_{Total} = I_1 + I_2$):** `_______ mA`
>
> **Conclusion:** > [Insert your observation here. *Hint: In a parallel circuit, contrast how voltage behaves across branches versus how current splits across them.*]

---