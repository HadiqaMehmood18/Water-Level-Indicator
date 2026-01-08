# Water Level Indicator - Digital Logic Design Project

A hardware-based water level monitoring system using **NOT Gate (IC 7404)** and basic electronic components. Simulated in Multisim and implemented on breadboard for practical demonstration of digital logic principles.

## 🔧 **Project Overview**
A cost-effective, electronic water level indicator that uses **IC 7404 (Hex NOT Gate)** to monitor and display water levels in tanks with visual LED indications for different levels: Empty, Low, Medium, Full, and Overflow.

## 🎯 **Key Features**
- **5-Level Visual Indication** using different colored LEDs
- **NOT Gate Logic** implementation using IC 7404
- **Transistor-based switching** (BC547 transistors)
- **Stable power supply** with 7805 voltage regulator
- **Breadboard implementation** for practical learning
- **Multisim simulation** for design verification

## 📦 **Components Used**
| Component | Quantity | Purpose |
|-----------|----------|---------|
| IC 7404 (NOT Gate) | 1 | Logic inversion for level detection |
| BC547 Transistors | 4 | Switching and signal amplification |
| LEDs (5mm) | 5 | Visual indicators (Red/Yellow/Green/White) |
| Resistors (10kΩ, 220Ω) | 4 each | Current limiting and biasing |
| Voltage Regulator 7805 | 1 | 5V regulated power supply |
| Breadboard | 1 | Circuit prototyping |
| 12V Battery | 1 | Power source |
| Connecting Wires | As needed | Circuit connections |
| Switches | 2 | Power and mode control |

## 🔌 **Circuit Operation**
1. **Water Level Probes** (not shown in simulation) detect water contact
2. **Transistor switching** based on water conductivity
3. **IC 7404 NOT Gates** invert signals for proper LED activation
4. **LED Indicators** show:
   - **Red**: Empty/Low level
   - **Yellow**: Medium level
   - **Green**: Full level
   - **White**: Overflow warning

## 💻 **Simulation & Tools**
- **Multisim 14+** for circuit simulation and testing
- **Breadboard implementation** for physical demonstration
- **Component testing** with multimeter
- **Logic analysis** of NOT gate behavior

## 📊 **Truth Table for Water Levels**
| Water Level | LED Status | Logic Output |
|-------------|------------|--------------|
| Empty | Red ON | 0001 |
| Low | Red ON | 0010 |
| Medium | Yellow ON | 0100 |
| Full | Green ON | 1000 |
| Overflow | White ON | 1111 |

## 🔍 **Key Advantages**
- **Low cost** compared to sensor-based systems
- **Simple design** easy to understand and implement
- **Reliable operation** with basic electronic components
- **Educational value** for learning digital logic
- **Low power consumption** suitable for battery operation

## ⚠️ **Limitations**
- Requires direct electrical contact with water
- Limited to 4-5 discrete levels
- Not suitable for corrosive liquids
- Manual calibration needed

## 🛠️ **Future Enhancements**
1. **IoT Integration** - WiFi/Bluetooth for remote monitoring
2. **Ultrasonic Sensors** - Non-contact level detection
3. **Automatic Pump Control** - Relay-based pump switching
4. **Mobile App Interface** - Real-time notifications
5. **Solar Power** - For remote/agricultural applications

## 👥 **Team Members**
- **Hadiqa Mehmood** (02-235232-007)
- **Esha Ashfaq** (02-235232-002)
- **Mahnoor Sharif** (02-235232-001)
- **Faiza Altaf** (02-235232-036)

## 📚 **Academic Information**
- **Course**: Digital Design Lab
- **Program**: BS(IT)-2A
- **Semester**: Spring 2024
- **University**: Bahria University Karachi
- **Instructor**: Sir Ismail Mansoor

## 📁 **Project Files**
- Multisim simulation file (.ms14)
- Circuit diagram/schematic
- Component list with specifications
- Testing procedures document

## 🔗 **Reference**
Project inspired by: [YouTube Tutorial](https://youtu.be/_hBA3PpnsyE)

---

**A practical implementation of digital logic concepts for real-world water management applications.**
