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
├── 📄 Collateral_Booklet_final.pdf     # Full design documentation
├── 📊 Morphology_chart.xlsx            # Design option analysis
├── 📈 Supporting_Calculations.xlsx     # Calculations for availability in Excel
├── 📐 calculation.pdf                  # Head-writing Calculation
├── 🎬 Fish Feeder Poster.pptx          # Presentation slide (limited in 1 page) with animations
├── 🌀 Screw_feeding_device.zip         # Solidworks model of the fish feeder
└── README.md                           # This file
```

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
- **Detailed diagrams**

---

## 🧪 Testing & Validation
- Simulated wind loading and buoyancy stability in Excel.
- Pneumatic pressure and flow calculations verified for nozzle performance.
- Solar energy yield vs. consumption validated for all-weather operation.
- Material selections (ABS, 316L stainless, PE, aluminum) meet food-grade, corrosion-resistant, and UV-stable requirements.

---

## 📈 Future Improvements
- IoT integration for cloud-based feeding schedules.
- Camera module for fish behavior monitoring.
- Enhanced predictive cleaning based on humidity sensors.
- Multi-tier pricing with extended battery and storage options.

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
