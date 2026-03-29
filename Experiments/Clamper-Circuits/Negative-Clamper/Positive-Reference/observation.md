# Negative Peak Clamper (Positive Reference)

## Input
- Square wave signal (~4 Hz)
- Positive DC reference applied

## Output Observations
- The waveform is shifted downward, but less compared to the no-reference case
- The positive peaks are clamped at a voltage above 0V
- The overall downward shift is reduced due to the positive reference
- The waveform shape remains unchanged

## Explanation
- During the positive half-cycle, the diode conducts and charges the capacitor along with the reference voltage
- During the negative half-cycle, the diode is reverse biased
- The capacitor stores a higher voltage due to the positive reference
- This reduces the net downward shift of the waveform

## Conclusion
Applying a positive reference raises the clamping level above 0V, reducing the downward shift of the waveform compared to the no-reference case.
