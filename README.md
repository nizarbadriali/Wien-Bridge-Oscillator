Wien Bridge Oscillator

82.2 kHz oscillator circuit using LT1007 op-amp.

Components
U1: LT1007 Op-Amp
Rf: 4.2 kΩ
Rg: 2 kΩ
R1, R2: 2 kΩ each
C1, C2: 1 nF each
V1, V2: ±5V supply
Frequency

82.2 kHz oscillation with ±3.6V output

How It Works

The Wien bridge uses matched RC networks (R1=R2=2k, C1=C2=1nF) to set frequency. The LT1007 provides gain through feedback resistors (Rf/Rg ratio) to sustain oscillation. Clean sine wave output with minimal distortion.

To Adjust Frequency

Change R1 and R2 together (keep them equal). Smaller resistance = higher frequency.

Notes
Use ±5V power supply
Keep components close to op-amp pins
Add 0.1µF bypass caps near power pins
1% tolerance resistors recommended for stability