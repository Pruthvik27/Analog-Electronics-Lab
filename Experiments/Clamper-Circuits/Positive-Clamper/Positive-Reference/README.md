# Positive Peak Clamper (Positive Reference)

## 📌 Objective

To study the effect of a positive reference voltage on a positive peak clamper circuit.

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

This circuit is a positive peak clamper with an external positive reference voltage applied.
The reference voltage modifies the clamping level of the output waveform.

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform is shifted upward significantly
* The negative peaks are clamped at a positive voltage level
* The DC level of the waveform increases due to the reference voltage
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the negative half-cycle, the diode conducts and charges the capacitor along with the reference voltage
* During the positive half-cycle, the diode becomes reverse biased
* The stored voltage in the capacitor adds to the input signal
* This results in a greater upward shift compared to the no-reference case

---

## 📊 Result

The circuit clamps the waveform to a positive voltage level (greater than 0V), determined by the applied reference voltage.

---

## 🔍 Key Difference from No Reference

* No Reference → Clamped at 0V
* Positive Reference → Clamped above 0V

---

## ✅ Conclusion

Applying a positive reference voltage increases the clamping level, shifting the waveform further upward while preserving its shape.
