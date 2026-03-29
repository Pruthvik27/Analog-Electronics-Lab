# Positive Peak Clamper (Negative Reference)

## 📌 Objective

To study the effect of a negative reference voltage on a positive peak clamper circuit.

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

This circuit is a positive peak clamper with an external negative reference voltage applied.
The negative reference alters the clamping level of the waveform.

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform shifts upward, but less than the positive reference case
* The negative peaks are clamped below 0V
* The DC level is reduced due to the negative reference voltage
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the negative half-cycle, the diode conducts and the capacitor charges considering the negative reference
* During the positive half-cycle, the diode becomes reverse biased
* The stored voltage is lower compared to other cases
* This results in a reduced upward shift of the waveform

---

## 📊 Result

The waveform is clamped at a negative voltage level, determined by the applied reference voltage.

---

## 🔍 Key Difference

| Case               | Clamping Level |
| ------------------ | -------------- |
| No Reference       | ~0V            |
| Positive Reference | Above 0V       |
| Negative Reference | Below 0V       |

---

## ✅ Conclusion

A negative reference voltage reduces the clamping level, causing the waveform to shift less upward compared to other cases while maintaining its shape.
