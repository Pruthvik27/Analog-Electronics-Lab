# Negative Peak Clamper (Negative Reference)

## Input
- Square wave signal (~4 Hz)
- Negative DC reference applied

## Output Observations
- The waveform is shifted further downward compared to the no-reference case
- The positive peaks are clamped at a voltage below 0V
- The negative peaks extend further into the negative region
- The waveform shape remains unchanged

## Explanation
- During the positive half-cycle, the diode conducts and charges the capacitor along with the negative reference voltage
- During the negative half-cycle, the diode is reverse biased
- The capacitor stores a larger effective voltage due to the negative reference
- This increases the downward shift of the waveform

## Conclusion
Applying a negative reference lowers the clamping level below 0V, increasing the downward shift of the waveform compared to the no-reference case.
