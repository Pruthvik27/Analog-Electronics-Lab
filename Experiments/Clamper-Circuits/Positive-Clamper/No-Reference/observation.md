# Positive Peak Clamper (No Reference)

## Input
- Square wave signal (~4 Hz)
- No external DC reference applied

## Output Observations
- The waveform is shifted upward along the voltage axis
- The negative peaks of the waveform are clamped near 0V
- The positive peaks rise above the original input amplitude
- The overall shape of the waveform remains unchanged

## Explanation
- During the negative half-cycle, the diode conducts and charges the capacitor
- During the positive half-cycle, the diode is reverse biased
- The stored voltage in the capacitor adds to the input signal, shifting it upward

## Conclusion
The positive peak clamper shifts the entire waveform upward such that the negative peaks are clamped at approximately 0V, without the use of any external reference voltage.
