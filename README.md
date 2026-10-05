# KHN State-Variable Filter PCB

Analog filter simulation and PCB design using LTspice and Altium Designer

---

### Overview

Designed and simulated a Kerwin-Huelsman-Newcomb (KHN) state-variable filter and translated the circuit into a complete PCB design

The filter provides three simultaneous outputs:

• High-Pass (HPF)  
• Band-Pass (BPF)  
• Low-Pass (LPF)

The project covers the workflow from circuit simulation and frequency-response analysis to schematic capture and PCB layout

---

### Applications

State-variable filters can be used when different frequency components of a signal need to be isolated or analyzed

Common applications include:

• Audio processing and equalization  
• Signal conditioning and noise filtering  
• Communications systems  
• Sensor signal processing  
• Instrumentation and measurement  
• Control systems  

A key advantage of the KHN architecture is that the high-pass, band-pass, and low-pass responses are available simultaneously from the same circuit.

---

### Circuit Simulation

The filter was recreated in LTspice and analyzed using an AC frequency sweep from 100 Hz to 1 MHz.

The simulation was used to examine the magnitude and phase response of the HPF, BPF, and LPF outputs.

Bode Plot

![Bode Plot](bode-plot.png)

---

### PCB Design

After verifying the circuit through simulation, the design was recreated in Altium Designer and converted into a PCB layout.

The PCB design process included:

• Schematic capture  
• Component and footprint selection  
• Component placement  
• Signal and power routing  
• PCB layout  
• Design-rule checking (DRC)

Altium Schematic



<img width="1754" height="878" alt="image" src="https://github.com/user-attachments/assets/82d0ce78-d056-4213-b4c1-9d82124c342d" />



PCB Layout


<img width="1662" height="1196" alt="image" src="https://github.com/user-attachments/assets/f159937c-d130-4af6-bc11-6dd67efb99bf" />

PCB Layout board design (3D)

<img width="532" height="532" alt="image" src="https://github.com/user-attachments/assets/b9b46e43-aafb-44fd-aa93-a7eb52ed9c13" />

---

### Design Workflow

    KHN Filter Architecture
             ↓
      LTspice Simulation
             ↓
      AC Frequency Sweep
             ↓
     Bode Plot Analysis
             ↓
       Altium Schematic
             ↓
    Footprint Selection
             ↓
      PCB Placement
             ↓
         Routing
             ↓
      Design Rule Check
             ↓
       Final PCB Layout

---

### Tools

LTspice  
Circuit simulation and frequency-response analysis

Altium Designer  
Schematic capture and PCB layout

GitHub  
Project documentation and version control

---

### Skills Demonstrated

Analog Circuit Design  
Operational Amplifiers  
Active Filters  
SPICE Simulation  
Bode Analysis  
Schematic Capture  
PCB Layout  
Component Selection  
PCB Routing  
Design Rule Checking

---

### Project Context

This project was completed as part of an analog electronics and PCB design course.

The objective was to take an analog filter from circuit simulation through PCB implementation, providing hands-on experience with the hardware design workflow.

---

### Future Work

• Fabricate and assemble the PCB  
• Measure the HPF, BPF, and LPF responses with an oscilloscope
• Compare measured results with LTspice simulation  
• Investigate component tolerance effects  
• Add test points for the filter outputs
