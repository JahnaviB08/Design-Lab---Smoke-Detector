# Laser Smoke Detector

Introduction

The Laser Smoke Detector is a project that utilizes laser diode, photodiodes, and operational amplifiers (op-amps) to detect the presence of smoke particles in the air. The laser diode emits a laser beam, and when smoke enters the detector chamber, particles scatter the laser light. A photodiode detects the scattered light. The op-amp circuitry is a transimpedance amplifier that converts the photocurrent produced in the photodiode to voltage. The output voltage is amplified and processed and used to trigger an alarm.

Key features

1. Highly senstive
2. Cost-effective (made the project under Rs. 1200)
3. Customizable threshold levels and alarm mechanisms.
4. Ideal for fire prevention and safety applications.

![smoke-detector](https://github.com/JahnaviB08/Design-Lab-Smoke-Detector/assets/109303093/59c92ebd-51ca-488f-9e71-6189479b728e)

Components used
1. Laser diode
2. Photodiodes (two photodiodes are used to cancel ambient noise and increase efficiency)
3. Operational amplifiers (e.g., LM741)
4. Resistors (for op-amp circuitry)
5. Breadboard and jumper wires or PCB for circuit assembly
6. Any microcontroller - used Arduino Uno
7. Power supply for the laser diode and op-amps (used power from arduino)
8. Alarm component - piezobuzzer
9. Enclosement for the detector - preferably a small black box.

Working Principle

The laser diode emits a focused laser beam into the air. In the absence of smoke particles, the photodiodes receive almost no light. And the small amount of ambient light present in the enclosement that falls on the photodiodes is processed in the microcontroller and cancelled. When smoke particles are present, they scatter the laser light in various directions. One of the photodiodes detects this scattered light. The transimpedance amplifier built using converts photocurrent into voltage and sends this output into arduino. The intensity difference the photodiode outputs is detected by the arduino and processed. If the signal exceeds a predefined threshold (indicating the presence of smoke), the alarm system (buzzer) is triggered.

Calibration

You can calibrate the laser smoke detector by adjusting the threshold levels. Experiment with different threshold values to optimize smoke detection sensitivity while minimizing false alarms.
