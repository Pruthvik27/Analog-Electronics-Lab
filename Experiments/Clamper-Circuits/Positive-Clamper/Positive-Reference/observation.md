# Positive Peak Clamper (Positive Reference)

## Input
- Square wave signal (~4 Hz)
- Positive DC reference applied

## Output Observations
- The waveform is shifted upward more than the no-reference case
- The negative peaks are clamped at a positive voltage level (above 0V)
- The entire waveform is elevated due to the applied reference voltage
- The shape of the waveform remains unchanged

## Explanation
- During the negative half-cycle, the diode conducts and charges the capacitor along with the reference voltage
- During the positive half-cycle, the diode is reverse biased
- The capacitor retains the combined voltage (input + reference)
- This causes the output waveform to shift further upward

## Conclusion
The positive reference increases the clamping level above 0V, resulting in a higher upward shift of the waveform compared to the no-reference case.
