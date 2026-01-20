# Autonomous Smart Fish Feeder – Outdoor Self-Cleaning System

## 🎯 Overview
This is a fully integrated, solar-powered automatic fish feeder designed for long-term outdoor deployment in lakes, ponds, and aquaculture environments. It combines **modular mechanical design**, **real-time electronic control**, **environmental sensing**, and **automated maintenance** into one robust, hands-free system capable of operating for over a week without human intervention.

The feeder meets strict functional and environmental requirements, including uniform feed dispersion over 28–80 m², daily dispensing of 2 kg of food, wind resistance up to 80 km/h, and operation in temperatures from 0–35°C.

---

## ✨ Key Features
- **8-Module Triangular Storage**: ABS plastic containers with built-in load cells and Raspberry Pi-controlled flip-lid valves for precise daily portions (16 kg total capacity).
- **Stainless Steel Screw Conveyor**: Polished auger with forced-air anti-clogging and low-energy stepper motor drive.
- **Pneumatic Sprinkler System**: 4 adjustable nozzles with PTFE lining for uniform horizontal dispersion via compressed air.
- **Solar-Powered with MPPT**: 10W monocrystalline panel + 12V 20Ah LiFePO₄ battery, supporting 7+ days of backup operation.
- **Raspberry Pi 4B Control**: Custom MATLAB/Python scripts for scheduling, sensor logging, remote monitoring, and fault alerts.
- **Self-Cleaning Subsystem**: Uses ambient water to flush residues weekly, preventing blockages.
- **Triple Bird Deterrence**: Reflective PET layer + stainless steel mesh + dynamic alarm.
- **Wind & Water Resistant**: 4 PE buoys with anchored stabilization, proven stable in 80 km/h winds.
- **LCD Status Display**: Real-time battery and food capacity monitoring.

---

## 📁 Project Structure
```
├── 📄 Collateral Booklet.pdf           # Full design documentation
├── 📊 Morphology chart.xlsx            # Design option analysis (Morphology Chart)
├── 📈 Supporting Calculations.xlsx     # Detailed engineering calculations
├── 📐 calculation.pdf                  # Handwritten core calculation process
├── 🌀 Fish_Feeder_Solidworks_Models.zip # Complete 3D Solidworks models (hosted externally) 🔗
└── README.md                           # This file
```
🔗 **External Model Download: The complete Solidworks assembly is available for download [here](https://nottinghamedu1-my.sharepoint.com/:u:/g/personal/ssyzz32_nottingham_edu_cn/IQA3pZ69PzgnS7V3GZmcSEUvAfplTpRjcfVD-lP991K43vo?e=fe6gYp).**


---

## ⚙️ Technical Specifications
| Component | Details |
|-----------|---------|
| Solar Panel | 10W monocrystalline with MPPT |
| Battery | 12V 20Ah LiFePO₄ |
| Controller | Raspberry Pi 4B + MATLAB/Python |
| Motor | 57HS22 stepper (12V, 3 RPM) |
| Air Pump | 12V, 0.7–10 bar |
| Water Pump | 12V, 2 L/min |
| Food Capacity | 16 kg (~8 days) |
| Dispersion Area | 28–80 m² |
| Wind Resistance | 80 km/h |
| Operating Temperature | 0–35°C |

---

## 🧮 Engineering Highlights
- **Dispersion Physics**: Calculated projectile motion to achieve 14.616–32.675 m/s nozzle velocity for even spread.
- **Power Budget**: Total daily consumption 219.77 Wh, solar supply 602.25 Wh/day — significant surplus for cloudy conditions.
- **Stability Analysis**: Metacentric height GM = 2.043 m > 0, with restoring moment > wind moment at 80 km/h.
- **Anti-Clogging**: Polished surfaces + fan-assisted drying + weekly water flush.
- **Cost Optimized**: Bill of materials controlled under target budget with standard parts (SKF bearings, stainless fasteners, silicone seals).

---

## 🛠️ How It Works
1. **Storage**: 8 triangular modules hold pre-weighed food.
2. **Metering**: Screw conveyor transfers exact portion to ejection chamber.
3. **Dispersion**: Pressurized air blows food through 4 nozzles over adjustable area.
4. **Control**: Raspberry Pi triggers valves, logs data, manages power.
5. **Cleaning**: Weekly water pump cycle cleans conveyor and nozzles.
6. **Protection**: Reflective layer, steel mesh, and alarms deter birds.

---

## 📸 Media & Demonstrations
- **Animated assembly and operation sequences**  
<div align="center">
<img src="https://github.com/ZEbirds/Autonomous-Fish-Feeder-Design/blob/main/Media%20%26%20Demonstrations/Animation%20for%20fish%20feeder.gif" width="600" height="400">
</div>

- **Detail diagram for Modular units**  
<div align="center">
<img src="https://github.com/ZEbirds/Autonomous-Fish-Feeder-Design/blob/main/Media%20%26%20Demonstrations/Diagram%20for%20Modular%20units.gif" width="600" height="400">
</div>

- **Detailed diagram for screw conveyor**  
<div align="center">
<img src="https://github.com/ZEbirds/Autonomous-Fish-Feeder-Design/blob/main/Media%20%26%20Demonstrations/Diagram%20for%20screw%20conveyor.gif" width="600" height="400">
</div> 

- **Detailed diagram for fish feeder**  
<div align="center">
<img src="https://github.com/ZEbirds/Autonomous-Fish-Feeder-Design/blob/main/Media%20%26%20Demonstrations/Diagram%20for%20fish%20feeder.png" width="600" height="400">
</div>  

---

## 🧪 Testing & Validation
- Simulated wind loading and buoyancy stability in Excel.
- Pneumatic pressure and flow calculations verified for nozzle performance.
- Solar energy yield vs. consumption validated for all-weather operation.
- Material selections (ABS, 316L stainless, PE, aluminum) meet food-grade, corrosion-resistant, and UV-stable requirements.

---

## 👥 Team & Acknowledgments
Developed as an engineering project supervised by Prof.Yong Ren with contributions in:
- Mechanical design & prototyping
- Electronics & power systems
- Control software & sensor integration
- Environmental testing & validation
Really apprieciate for Prof Ren's Instruction and Support!

---
*For more details, refer to the full design booklet and calculation files in this repository.*
