# AUX-to-Bluetooth Audio Transmitter

This is a custom-designed PCB that turns any wired audio source into a Bluetooth transmitter. Plug an old record player, TV, or PC into the 3.5mm AUX jack, and stream clean audio wirelessly to your Bluetooth headphones or speakers like AirPods.

## What It Does

* **Wired to Wireless:** Takes analog audio from a standard 3.5mm auxiliary cable.
* **High-Quality Conversion:** Converts analog signals into a clean digital I2S audio stream.
* **Bluetooth Streaming:** Uses an ESP32 microcontroller to transmit the audio over Bluetooth to your wireless gear.
* **External Antenna:** Includes an RP-SMA antenna connection so you get great wireless range without dropouts.

## Key Hardware Components

* **ESP32-WROOM-32UE-N4:** The main brain handling Bluetooth pairing, audio routing, and wireless streaming.
* **PCM1808PWR:** A 24-bit stereo ADC that turns your analog sound into digital data.
* **AP2112K-3.3:** A low-dropout voltage regulator that steps down USB power to a steady 3.3V.
* **CH340C:** A USB-to-UART bridge chip for easy programming and debugging via USB-C.
* **SJ-3523-SMT-TR:** The surface-mount 3.5mm stereo audio jack for your input cable.
* **Passive Parts:** 0805 ceramic capacitors and resistors used for power filtering and signal coupling.

## Power and Setup

1. Plug the board into a standard USB-C power source or computer port.
2. Connect your audio source to the 3.5mm AUX jack.
3. Put your Bluetooth headphones or earbuds into pairing mode and let the ESP32 connect.

<img width="927" height="317" alt="image" src="https://github.com/user-attachments/assets/ea6fbd94-fed4-4347-8195-9e7ccd699d3b" />

<img width="1337" height="637" alt="image" src="https://github.com/user-attachments/assets/ecf68d2b-bb41-400f-ab80-939498a8456c" />

<img width="806" height="392" alt="image" src="https://github.com/user-attachments/assets/452a5d86-8714-4715-b7d8-b53c9003d279" />


