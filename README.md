# Scope-Measurements-RC-Filters
Analysis of periodic signals and frequency response of RC low-pass filters using a Digital Storage Oscilloscope (DSO)


## 📌 Overview
This repository documents the results of Laboratory 1 for the **Instrumentation and Measurement (EEL2)** module. The project focuses on mastering the Digital Storage Oscilloscope (DSO) for signal characterization and performing frequency-domain analysis on an RC network.

## 🛠 Setup & Equipment
* **Oscilloscope:** Tektronix TDS 3014B Digital Storage Oscilloscope
* **Multimeter:** Digital Voltmeter (Type 18S)
* **Circuit Components:** * Resistor ($R$): $2.2\text{ k}\Omega$
    * Capacitor ($C$): $47\text{ nF}$
* **Software/Tools:** Signal Generator, Logarithmic Plotting.

---

## 🔬 Experimental Work

### 1. Signal Characterization
Verified the properties of Sine, Square, and Triangle waves at a fundamental frequency of $800\text{ Hz}$. 
* **Key Objective:** Comparing peak-to-peak voltage ($U_{pp}$), effective voltage ($U_{eff}$), and mean values between theoretical formulas and measured data.
* **Findings:** Confirmed mathematical relationships for RMS values and observed the effect of DC offsets on mean voltage measurements.

### 2. RC Low-Pass Filter (Bode Plot)
Characterized the frequency response of a first-order low-pass filter by sweeping frequencies from $100\text{ Hz}$ to $100\text{ kHz}$.
* **Cutoff Frequency ($f_c$):** Theoretically calculated at $\approx 1.54\text{ kHz}$.
* **Gain & Phase:** Measured the output voltage ($U_C$) and the time delay ($\Delta t$) to determine the phase shift ($\phi$).
* **Roll-off:** Successfully mapped the -20 dB/decade roll-off characteristic on a logarithmic scale.

---

## 📂 Project Structure
* `/reports`: Scanned handwritten data tables and measurement logs.
* `/plots`: Logarithmic Bode diagrams (Gain and Phase).
* `/signals`: Oscilloscope captures showing trigger stabilization and signal comparison.

## 💡 Key Skills Demonstrated
* **Signal Integrity:** Analyzing the difference between AC and DC coupling on signal visualization.
* **Instrument Calibration:** Adjusting triggering levels and slope to stabilize non-sinusoidal waveforms.
* **Analytical Engineering:** Bridging the gap between circuit theory and real-world measurement error margins.

<img width="1600" height="1090" alt="WhatsApp Image 2026-05-08 at 10 59 55" src="https://github.com/user-attachments/assets/41d349b4-d17c-4328-a8bc-dfd35185a332" />
<img width="1600" height="1036" alt="WhatsApp Image 2026-05-08 at 10 59 55 (1)" src="https://github.com/user-attachments/assets/66a917eb-669b-4705-b6d5-c35332b4b1ac" />
<img width="1200" height="1600" alt="WhatsApp Image 2026-05-08 at 10 59 49" src="https://github.com/user-attachments/assets/c293075b-d4ca-4023-b4f0-a2b9c7a8463a" />
<img width="1600" height="1054" alt="WhatsApp Image 2026-05-08 at 10 59 37" src="https://github.com/user-attachments/assets/73c13713-b9c3-4026-b5d6-ff5de54b9cb0" />
<img width="1600" height="949" alt="WhatsApp Image 2026-05-08 at 10 59 47" src="https://github.com/user-attachments/assets/ae8027a7-322e-45f7-81ab-1aea7a706a24" />





