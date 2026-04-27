# ⚙️ Calibration Data – Low Cost 3D Printer

This document contains all calibration parameters used for tuning the performance and accuracy of the 3D printer.

---

## 🔧 Firmware Calibration (Marlin)

### Steps per mm
- X-axis: 102
- Y-axis: 103
- Z-axis: 400
- Extruder (E): 95

### Maximum Feedrate (mm/s)
- X: 300
- Y: 300
- Z: 5
- E: 25

### Acceleration (mm/s²)
- X/Y: 1000
- Z: 100
- E: 1000

---

## 🌡️ Temperature Settings

- Nozzle Temperature: 200°C (PLA)
- Bed Temperature: 60°C
- Thermistor Type: 100k NTC

---

## ⚙️ Slicer Settings (Cura Standard Profile)

- Layer Height: 0.2 mm
- Print Speed: 50 mm/s
- Travel Speed: 120 mm/s
- Initial Layer Speed: 20 mm/s
- Infill Density: 20%
- Infill Pattern: Grid

---

## 🧪 Test Results

### Calibration Cube (20mm)
- Measured X: 19.9 mm
- Measured Y: 20.0 mm
- Measured Z: 19.95 mm
- Result: Acceptable accuracy

### Extrusion Test
- Commanded: 100 mm
- Actual: 98–100 mm
- Result: Minor tuning applied

---

## 🛠️ Calibration Methods

- Steps/mm calibrated using test prints
- Extruder calibrated using filament measurement test
- Bed leveling performed manually
- Temperature verified using stable print results

---

## 📌 Notes

- Ensure proper cooling of A4988 drivers
- Regularly check belt tension for accuracy
- Recalibrate after hardware changes
