# Negative Peak Clamper (Positive Reference)

## 📌 Objective

To study the effect of a positive reference voltage on a negative peak clamper circuit.

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

This circuit is a negative peak clamper with an external positive reference voltage applied.
The reference voltage modifies the clamping level of the output waveform.

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform shifts downward, but less than the no-reference case
* The positive peaks are clamped above 0V
* The DC level is increased due to the positive reference voltage
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the positive half-cycle, the diode conducts and charges the capacitor along with the reference voltage
* During the negative half-cycle, the diode becomes reverse biased
* The stored voltage opposes the downward shift
* This results in a reduced downward shift compared to the no-reference case

---

## 📊 Result

The waveform is clamped at a positive voltage level (above 0V), determined by the applied reference voltage.

---

## 🔍 Key Difference

| Case               | Clamping Level |
| ------------------ | -------------- |
| No Reference       | ~0V            |
| Positive Reference | Above 0V       |
| Negative Reference | Below 0V       |

---

## ✅ Conclusion

A positive reference voltage raises the clamping level, reducing the downward shift of the waveform while preserving its shape.
