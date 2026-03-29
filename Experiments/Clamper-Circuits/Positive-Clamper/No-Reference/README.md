# Positive Peak Clamper (No Reference)

## 📌 Objective

To study the working of a positive peak clamper circuit without any external reference voltage.

---

## 🔧 Components Used

* Diode (1N4148 / 1N4007)
* Capacitor
* Resistor
* Function Generator
* Oscilloscope

---

## ⚙️ Circuit Description

The circuit consists of a diode, capacitor, and resistor.
No external DC source is used (No Reference condition).

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform is shifted upward along the voltage axis
* The negative peaks are clamped near 0V
* The positive peaks increase above the original amplitude
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the negative half-cycle, the diode becomes forward biased and charges the capacitor
* During the positive half-cycle, the diode is reverse biased
* The capacitor retains its charge and adds to the input signal
* This results in an upward shift of the entire waveform

---

## 📊 Result

The circuit successfully clamps the negative peaks of the waveform to approximately 0V, effectively shifting the waveform upward without using any external reference voltage.

---

## ✅ Conclusion

A positive peak clamper without reference acts as a DC restorer by shifting the signal upward while maintaining its original shape.
