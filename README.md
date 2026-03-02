<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [] 🎯

## Basic Details

### Team Name: [Dual Core]

### Team Members
- Member 1: [Anaan Shaji] - [College Of Engineering]
- Member 2: [Alphy Aby] - [College Of Engineering]

### Hosted Project Link
[mention your project hosted link here]

### Project Description
[This project develops a smart piezoelectric tile that converts footsteps into electrical energy. The generated voltage is measured using an Arduino to detect steps, estimate energy production, and monitor crowd levels. The system displays real-time data such as step count and peak voltage on an LCD, demonstrating a simple approach to energy harvesting in public spaces.]

### The Problem statement
[In crowded public places such as railway stations, malls, and college campuses, thousands of footsteps generate mechanical energy every day. This energy is normally wasted.]

### The Solution
[The solution uses piezoelectric sensors embedded in a tile to generate voltage from human footsteps. An Arduino reads the voltage signal to detect steps and measure the peak voltage produced. The system displays the step count and voltage values on an LCD screen, providing a simple method for monitoring foot traffic and generated voltage in real time.]

---

## Technical Details

### Technologies/Components Used

**For Hardware:**
- Main components: [35mm Piezo discs ,Arduino UNO,LCD I2C display,18650 cell,resistor , capacitor, diodes]
- Specifications: [35mm Piezo Disc-Generates voltage spikes when pressure is applied.
   Arduino UNO-Reads sensor input and controls display.16×2 I2C LCD Display-Shows step count and voltage in real time.]
- Tools required: [Mini Breadboard,Hookup wires,Jumper wires,Arduino IDE, LCD Library, Soldering Iron]

---

## Features

List the key features of your project:
- Feature 1: [Detects footsteps using piezoelectric sensors.]
- Feature 2: [Measures and displays the maximum voltage generated so far.]
- Feature 3: [Counts steps and shows the total on an LCD display.]
- Feature 4: [Works as a simple demonstration of energy harvesting from footsteps.]

---

## Implementation

### For Hardware:

#### Components Required
[35mm Piezo Disc

Generates voltage spikes when pressure is applied.

Arduino UNO

Reads sensor input and controls display.

16×2 I2C LCD Display

Shows step count and voltage in real time.

1N4007 Diode

Converts AC from piezo to DC.

10µF Capacitor

Stores the rectified voltage temporarily.

18650 Battery

Provides portable 3.7V power supply.

I2C LCD Pins

SDA → A4, SCL → A5, VCC → 5V, GND → GND.
]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](<p align="center">
  <img src="teamphoto.png" alt="team photo" width="100%">
</p>)

![Components](Add photo of your components here)
*List out all components shown*

![Build](<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>
)


![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹260 | [Link] |
| LED | 1| green, 5mm, 20mA | ₹2 each | [Link] |
| Resistor | 3 | 100kΩ,10kΩ, 330Ω | ₹1 each | [Link] |
| Mini Breadboard | 1 | 400 points | ₹50 | [Link] |
| Jumper Wires | 30 | Male-to-Male, Male to female | ₹2 each | [Link] |
| Piezoelectric Disc | 6|  35mm      |₹15 each| |
|capacitor|1| 10uf|₹2.5||
|LCD Display|1|16*2 I2C|₹175|

**Total Estimated Cost:** ₹[850]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---



## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g. ChatGPT]

**Purpose:** [What you used it for]
-  "AI helped us find the most efficient way to connect and use our components."
-  "For circuit Debugging assistance "
-  "Code review and optimization suggestions"
-  Understanding piezoelectric working principle
-  Drafting presentation scripts

**Key Prompts Used:**
- "Check if this circuit setup will correctly charge the capacitor from the piezo discs.”
- "Suggest ways to reduce energy loss in the connections and diodes"
- Modify Arduino code to display actual voltage instead of analog value.
- How to measure real-time voltage from piezo using Arduino?
  
**Percentage of AI-generated code:** [Approximately 30%]

**Human Contributions:**
Designed the system architecture and circuit layout
Assembled and wired the hardware components
Developed and modified the Arduino code
Integrated hardware and software components
Tested, debugged, and calibrated the system

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Anaan Shaji]: [Contributed to system architecture planning, assembled and wired the hardware components including the piezo sensor and voltage divider, Implemented Arduino code, supported system integration, and participated in testing, debugging, documentation, and presentation.]
- [Alphy Aby]: [Contributed to system architecture planning, developed and modified the Arduino code, integrated the LCD display and transistor circuit, assisted in hardware assembly and wiring, and participated in system integration, testing, debugging, documentation, and presentation.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
