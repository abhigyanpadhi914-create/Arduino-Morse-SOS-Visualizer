# 🚨 Arduino Morse SOS Visualizer

An Arduino-based project that translates the **SOS** (... --- ...) Morse code signal into visual pulses using a 7-LED array.

## 🛠️ Hardware Setup
* **Microcontroller:** Arduino Uno R3
* **LEDs:** 7x Assorted Colors (Red, Blue, Green)
* **Resistors:** 7x 220Ω 
* **Connection:** Pin 13 (Primary Signal)

## 📸 Demo
[Insert your screen recording or GIF here]

## 💻 How It Works
The code uses a modular function `blinkMorse()` to handle the timing for dots (200ms) and dashes (600ms). This ensures the signal follows international Morse code standards.
