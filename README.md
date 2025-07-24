# DIY Audio Surveillance Kit

> Open-source wireless surveillance prototype for educational testing, electronics research, and DIY signal monitoring.

## 🔧 Overview

This project enables the creation of a wireless audio surveillance device using affordable components like Arduino Nano and NRF24L01 modules. Designed for **controlled environments**, it's ideal for prototyping, signal testing, and educational purposes related to privacy and electronic security.

## 📦 Features

- Audio capture via condenser microphone  
- Signal amplification and digitization  
- Wireless transmission using RF modules  
- Optional receiver playback via mini speaker  
- Modular, expandable architecture

## 🚀 Use Cases

- Educational labs and workshops  
- Electronics debugging in test environments  
- Simulated security monitoring scenarios  
- Audio signal interception & analysis tutorials

> ⚠️ This project is intended **for educational use only**. Do not deploy or use in environments without explicit permission.

## 🧰 Hardware Requirements

| Component             | Quantity | Notes                           |
|----------------------|----------|---------------------------------|
| Arduino Nano          | 2        | Sender + Receiver               |
| Condenser Microphone  | 1        | Sound input                     |
| LM358 Op-Amp          | 1        | Audio amplification             |
| NRF24L01 Module       | 2        | RF communication                |
| 8Ω Mini Speaker       | 1        | Receiver playback               |
| TP4056 Module         | Optional | Battery charging (sender side)  |
| Li-Ion Battery        | Optional | Portable setup                  |
| Misc Components       | ✅       | Resistors, PCB, headers etc.    |

## 🧠 Software

- Arduino IDE  
- RF24 & RF24Audio libraries  
- Optional: Serial Monitor for debugging  
- Compatible with Linux / Windows

## 📂 Repository Structure

```
📁 diy-audio-surveillance-kit/
 ┣ 📂 Schematics/         # Circuit diagrams (.pdf, .png)
 ┣ 📂 ArduinoCode/        # Source code (.ino)
 ┣ 📂 Docs/               # Legal disclaimer, translations
 ┗ README.md              # Project introduction
```

## 📚 Docs & Translations

Persian translation available at 
............     محتوای فارسی   ............
[`Docs/README_FA.md`](Docs/README_FA.md)

## 📄 License

This project is distributed under the **MIT License**. It is intended for research, educational, and ethical development only.
