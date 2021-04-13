# Initial D: Gas Gas Gas - Pure Data Patch

The song loop is created using Hradio sequencers that reads MIDI values from an array which are converted to frequency. The array pattern is played
at the tempo designated by the metro object which loops by mod of float values incrementing by 1 for each metro bang. Sound sub patches are created with osc and noise objects.
Includes volume control sliders as well as low pass filter and delay built in to the melody.
