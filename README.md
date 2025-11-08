# .paris
.paris is a file format for interpreting morse based on CSV

1. Training and Decoding Research

Provides a ground-truth dataset for Morse decoding algorithms (e.g., DSP or ML systems).

Allows generation of training material with exact timing or simulated human variations.

Can be easily converted to audio or RF keying signals for Morse practice or decoder testing.

2. Signal Simulation and Testing

Useful for bench-testing receivers, SDR software, or decoding firmware.

Can simulate “imperfect” human keying, variable speeds, and noise-free waveforms using cutoffs.

Ideal for verifying timing tolerance in automatic decoders, measuring jitter handling, or evaluating keyer filters.

3. Educational Tools

Students or hams can visualize Morse as digital signals.

Demonstrates the relationship between timing, WPM, and human error.

4. Audio or RF Playback

You can use it to drive:

A microcontroller keying output (e.g., to key a transmitter or sidetone).

A software tone generator (Python, MATLAB, or SDR platforms).

This converts your CSV into a realistic CW signal playback with precise timing control.




binary waveform using thresholds :   __■■■■____■■■■■■■_____■■■___
vs a stadard aproach: __/‾‾‾‾‾\__/‾‾‾‾‾‾‾\____/‾‾‾\
