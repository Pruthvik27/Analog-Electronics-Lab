# Negative Peak Clamper (No Reference)

## 📌 Objective

To study the working of a negative peak clamper circuit without any external reference voltage.

---

## 🔧 Components Used

* Diode (1N4148 / 1N4007)
* Capacitor
* Resistor
* Function Generator
* Oscilloscope

---

## ⚙️ Circuit Description

The circuit consists of a diode, capacitor, and resistor arranged to shift the waveform downward.
No external DC reference voltage is used in this configuration.

---

## 📥 Input Signal

* Type: Square Wave
* Frequency: ~4 Hz

---

## 📤 Output Observations

* The waveform shifts downward along the voltage axis
* The positive peaks are clamped near 0V
* The negative peaks extend further below 0V
* The waveform shape remains unchanged

---

## 🧠 Working Principle

* During the positive half-cycle, the diode becomes forward biased and charges the capacitor
* During the negative half-cycle, the diode is reverse biased
* The stored voltage in the capacitor subtracts from the input signal
* This results in a downward shift of the waveform

---

## 📊 Result

The circuit successfully clamps the positive peaks of the waveform to approximately 0V, shifting the waveform downward without any external reference.

---

## 🔍 Key Insight

* Positive Clamper → shifts waveform upward
* Negative Clamper → shifts waveform downward

---

## ✅ Conclusion

A negative peak clamper without reference acts as a DC restorer by shifting the signal downward while maintaining its original shape.
