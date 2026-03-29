# Negative Peak Clamper (No Reference)

## Input
- Square wave signal (~4 Hz)
- No external DC reference applied

## Output Observations
- The waveform is shifted downward along the voltage axis
- The positive peaks are clamped near 0V
- The negative peaks extend below the original input level
- The shape of the waveform remains unchanged

## Explanation
- During the positive half-cycle, the diode conducts and charges the capacitor
- During the negative half-cycle, the diode is reverse biased
- The capacitor retains its charge and subtracts from the input signal
- This results in a downward shift of the waveform

## Conclusion
The negative peak clamper shifts the entire waveform downward such that the positive peaks are clamped at approximately 0V, without using any external reference voltage.
