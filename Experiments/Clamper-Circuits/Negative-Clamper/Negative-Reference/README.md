# Negative Peak Clamper (Negative Reference)

## 📌 Objective

To study the effect of a negative reference voltage on a negative peak clamper circuit.

---

## 🔧 Components Used

* Diode (1N4148 / 1N4007)
* Capacitor
* Resistor
* Function Generator
* Oscilloscope
* DC Power Supply

---

## ⚙️ Circuit Description

This circuit is a negative peak clamper with an external negative reference voltage applied.
The reference voltage shifts the clamping level further below 0V.

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform shifts further downward
* The positive peaks are clamped below 0V
* The negative peaks extend deeper into the negative region
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the positive half-cycle, the diode conducts and charges the capacitor along with the negative reference voltage
* During the negative half-cycle, the diode becomes reverse biased
* The stored voltage adds to the downward shift
* This results in a greater negative displacement of the waveform

---

## 📊 Result

The waveform is clamped at a negative voltage level (below 0V), determined by the applied reference voltage.

---

## 🔍 Key Difference

| Case               | Clamping Level |
| ------------------ | -------------- |
| No Reference       | ~0V            |
| Positive Reference | Above 0V       |
| Negative Reference | Below 0V       |

---

## ✅ Conclusion

A negative reference voltage lowers the clamping level further, increasing the downward shift of the waveform while maintaining its original shape.
