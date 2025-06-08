# Hydroelectric Energy Logger

A small-scale Pelton turbine test rig with voltage/current sensing to evaluate hydroelectric efficiency at various flow rates and heads.

---

### ⚙️ Hardware Design
- 12V DC motor as Pelton turbine generator
- Flow sensor, pressure sensor
- ESP32 for data logging and wireless transmission

---

### 🧠 Control/Software Features
- Sample power data at 1 Hz
- Calculate efficiency: (V x I) / (flow x head)
- Export CSV logs via Wi-Fi or SD

---

### 📊 Results (Expected)
- Efficiency data at 3 different flow rates
- Ideal head range for max output
- Compare load effect (resistive vs. dump)

---

### 🧰 Tools Used
- Arduino IDE (ESP32)
- Python (pandas, matplotlib)
- KiCad

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
