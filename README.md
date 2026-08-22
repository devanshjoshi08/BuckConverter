# ⚡ Buck Converter
### High-Efficiency Step-Down DC-DC Supply, Designed and Fabricated End to End

---

## 📌 Project Overview

A buck converter is a high-efficiency power conversion circuit that steps a higher input voltage down to a lower output voltage for a load. Instead of burning off the difference as heat the way a resistor divider would, it uses switching MOSFETs and an LC filter to regulate the output efficiently, typically above 90 percent.

This project covers the full hardware design cycle: schematic capture, PCB layout, Gerber generation for fabrication, hand assembly of the manufactured board, and bench testing.

**Author:** Devansh Joshi

---

## ✨ Highlights

- End-to-end hardware build, from schematic to a working soldered board
- Switching-regulator topology targeting greater than 90 percent efficiency
- Custom two-layer PCB laid out in KiCad with fabrication-ready Gerber files
- Verified on the bench with an oscilloscope, function generator, and digital multimeter

---

## 🖼 Final Board

![Assembled buck converter board](Images/FinalProduct.png)

---

## 🛠 Design Cycle

1. **Schematic capture** - Designed the converter in KiCad, choosing the switching stage, inductor, and output filtering for step-down regulation.
2. **PCB layout** - Placed and routed a custom two-layer board, keeping the switching loop tight to limit noise.
3. **Fabrication** - Exported Gerber and drill files and had the board manufactured.
4. **Assembly** - Soldered the components onto the manufactured board by hand.
5. **Testing** - Characterized the board with an oscilloscope, function generator, and digital multimeter to confirm step-down operation.

---

## 📂 Repository Layout

```
BuckConverterLab/            KiCad project (schematic and PCB layout)
BuckConverter_GerberFiles/   Fabrication-ready Gerber and drill files
Images/                      Photos of the assembled board and test results
```

---

## 🧰 Skills Demonstrated

- Analog and power electronics design
- Schematic capture and PCB layout in KiCad
- Design for manufacturing: Gerber export and fabrication handoff
- Board assembly and soldering
- Bench characterization and debugging with lab instruments
