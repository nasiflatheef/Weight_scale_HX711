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
- Supporting components: resistors, capacitors, etc.

## Software Requirements
- Arduino IDE or PlatformIO.
- HX711 library by Bogde.
- Python 3.x (for tools).

## Getting Started

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/weight-scale.git
    cd weight-scale
    ```

2. Install dependencies:
    - Install the HX711 library via Arduino Library Manager.

3. Upload the code:
    - Open `code/src/main.cpp` in Arduino IDE.
    - Configure your COM port and upload to ESP32.

4. Calibrate the scale:
    - Use the calibration tool (`tools/calibration_tool.py`) to calibrate your load cell.

5. Start measuring weights!

## Documentation
Refer to the [docs](docs/) folder for detailed guides:
- [System Architecture](docs/architecture.md)
- [Calibration Guide](docs/calibration_guide.md)
- [Troubleshooting](docs/troubleshooting.md)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
