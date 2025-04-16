# Weight Scale Using HX711 and ESP32

This project implements a digital weight scale using the HX711 ADC and ESP32 microcontroller. The system is designed to measure weights accurately and can be calibrated easily.

## Features
- Accurate weight measurement using HX711.
- Real-time data logging to a connected device.
- Calibration tool for precise measurements.
- Modular codebase for easy expansion.

## Hardware Requirements
- ESP32 microcontroller.
- HX711 load cell amplifier.
- Load cell (e.g., 5kg strain gauge).


## Software Requirements
- Arduino IDE or PlatformIO.
- HX711 library by Rob Tillaart.

## Getting Started
![Schematic](https://github.com/user-attachments/assets/4376e429-1911-47bc-9b25-4c5b896578d7)

1. Clone the repository:
    ```
    git clone [https://github.com/yourusername/weight-scale.git
    cd weight-scale](https://github.com/RobTillaart/HX711)
    ```

2. Install dependencies:
    - Install the HX711 library by Rob Tillaart via Arduino Library Manager.

3. Upload the code:
    - Copy the code to Arduino IDE.
    - Configure your COM port and upload to ESP32.

4. Calibrate the scale:
    - Use the calibration code to calibrate your load cell.

5. Start measuring weights!
