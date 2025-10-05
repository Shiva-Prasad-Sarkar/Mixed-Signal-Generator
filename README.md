
# 🔀 Mixed Signal Generator Using Operational Amplifiers

This repository documents the design and hardware implementation of a Mixed Signal Generator capable of producing square, triangular, and sine waveforms using UA741 operational amplifiers. Built for the CSE350: Digital Electronics and Pulse Techniques course at BRAC University, this project emphasizes analog waveform synthesis using basic components on a breadboard.

## 📡 Waveforms Generated

- ✅ Square Wave — via Schmitt Trigger
- 🔺 Triangular Wave — via Integrator Circuit
- 🌊 Sine Wave — via Wien Bridge Oscillator

## 🧠 Theory of Operation

The signal generator is composed of three stages:

| Stage                  | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Schmitt Trigger        | Generates a stable square wave using positive feedback                      |
| Integrator             | Converts square wave into a triangular waveform                             |
| Wien Bridge Oscillator | Produces a sine wave using frequency-selective feedback                     |

## 🔧 Hardware Components

- UA741 Op-Amps  
- Resistors & Capacitors (standard values)  
- Breadboard & Jumper Wires  
- Potentiometer (0–100k)  
- Dual DC Power Supply (±15V)

## 🛠️ Circuit Highlights

- **Schmitt Trigger**: Sharp transitions, hysteresis-based square wave
- **Integrator**: Clean triangular wave from square input
- **Wien Bridge Oscillator**: Tuned sine wave with amplitude stabilization

## 📷 Experimental Setup

- Breadboard assembly of all three circuits
- Oscilloscope screenshots of waveform outputs
- Component tuning for waveform purity and stability

## ⚠️ Challenges & Solutions

| Challenge                          | Solution                                                                 |
|-----------------------------------|--------------------------------------------------------------------------|
| Wien bridge amplitude instability | Added incandescent bulb for automatic gain control                       |
| No output with polarized capacitors | Switched to non-polarized capacitors for correct waveform generation     |
| Breadboard noise                  | Used shorter jumpers and cleaner layout to reduce interference           |
| Component tolerances              | Empirical tuning of resistors and capacitors for desired frequencies     |

## ✅ Results

- Square wave: Stable and sharp
- Triangular wave: Clean linear ramps
- Sine wave: Smooth and tunable via Wien bridge

## 🚀 Future Improvements

- Digital frequency control  
- Amplitude modulation  
- Additional waveforms (e.g., sawtooth, PWM)  
- PCB design for compact implementation

## 👥 Team Members

- Aditi Roy Adri — 23101314  
- Shiva Prasad Sarkar — 23101302  
- Shafi Ahmed Adib — 23101307  
- Tasfia Islam — 23101481  

Group 4, Section 11 — BRAC University

## 📚 References

- Sedra & Smith, *Microelectronic Circuits*  
- Horowitz & Hill, *The Art of Electronics*  
- Razavi, *Design of Analog CMOS Integrated Circuits*  
- Marston, *Operational Amplifiers and Linear Integrated Circuits*


